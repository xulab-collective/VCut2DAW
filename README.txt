=================================================================================================
VCut2DAW // Xulab Collective
Open-Source Video-to-DAW Conform & Scene Marker Pipeline
[ Architects: @Rhinofug & @Parapazula  |  Compute: 100% Local  |  License: GNU AGPLv3 ]
=================================================================================================

For digital workers, against capital monopoly in the market and the system of exploitation: VCut2DAW is an open-source
post-production pipeline tool forged by Xulab Collective to eliminate mechanical conform drudgery
and reclaim time for Sound Editors, Dialogue Editors, Re-Recording Mixers, and Assistant Editors.

It automatically detects visual cuts from a video or parses CMX3600 EDLs and generates 100%
compliant Dummy AAFs and Frame-Accurate MIDI Markers synced for Pro Tools, Nuendo, Reaper, Logic, and other DAWs.

Collective & Docs      : https://github.com/xulab-collective  |  https://xulab-collective.github.io
Architects             : Furkan Utku Gercik // @Rhinofug - Founding Architect
                         Muhammed Kol // @Parapazula - Co-Architect
Repository             : https://github.com/xulab-collective/VCut2DAW
Discord Commons        : https://discord.gg/ZCFHD5qHgJ
Broadcast Channels     : https://t.me/xulabcollective  |  WhatsApp: https://whatsapp.com/channel/0029VbEM99jDuMRWtFLqta2f  |  https://www.youtube.com/@xulab-collective

-------------------------------------------------------------------------------------------------

## Why This Exists // The Technical Edge

1. DAW AAF Strictness: Pro Tools 12.5+ aggressively rejects standard OTIO AAFs. VCut2DAW uses pyaaf2
   to build compliant SourceMob/MasterMob hierarchies so DAWs never throw an import error.
2. Fractional Frame Rate & Sample-Accurate Sync // 23.976, 29.97, 59.94: Uses exact broadcast rational
   ratios 24000/1001, 30000/1001, and 60000/1001 plus absolute sample/tick accumulation at 48 kHz so cuts
   never drift across 160-minute broadcast episodes or feature-length timelines.
3. The 1-Frame Drift Fix: Automated cut detection often places the cut on the first new frame, resulting
   in a 1-frame offset compared to traditional NLE edits. This tool converts detected cuts to 0-based
   frames. EDL cuts are not shifted.
4. The 120 BPM MIDI Sync Fix: DAWs tie MIDI marker timecodes to the session tempo map. This tool
   writes a Type 1 MIDI file at Pro Tools' native 960 PPQ with a fixed 120 BPM tempo at 1920 ticks/sec,
   ensuring timecodes land accurately without overflow.

-------------------------------------------------------------------------------------------------

## Core Capabilities

- One-Click Video to Cuts: Select an MP4/MOV/MKV/AVI and get frame-accurate CSV, MIDI Markers, and Dummy AAF.
- Auto & Manual Frame Rate Support: Automatically detects 23.976, 24, 25, 29.97, 30, 50, 59.94, 60 FPS or allows manual override.
- EDL Support: Load a standard CMX3600 .edl file directly via the collapsible Advanced panel.
- Dummy AAF Generation: Generates a Clip Track allowing you to use 'Tab to Transient' to jump between scenes.
- Clean Output Structure: Automatically creates a VCut2DAW_Exports parent folder right next to your video.
- Session Start Timecode Offset: Input your session start such as 01:00:00:00 and the files will spot accurately.

-------------------------------------------------------------------------------------------------

## System Requirements & DAW Compatibility

- Pro Tools: Pro Tools 10, 11, 12.5 through Pro Tools 2025.12+ across Studio, Ultimate, and HD.
  * PT 2022.9 - 2025.12+: Full support for Global Ruler Markers up to 32k, Track Markers, and Dummy AAF.
  * PT 10 / 11 / 12.5 - 2022.7: Full Dummy AAF Clip Track support with unlimited cuts plus MIDI Markers up to 999 Memory Locations.
- Pro Tools Intro / First: MIDI Markers supported; AAF import is disabled by Avid in free editions.
- Other DAWs: Nuendo, Cubase, Logic Pro, Reaper, Studio One, DaVinci Resolve Fairlight.
- Windows: Windows 10 & Windows 11 64-bit.
- macOS: macOS 11 Big Sur through macOS 15 Sequoia+ across Apple Silicon M1/M2/M3/M4 & Intel x64.

-------------------------------------------------------------------------------------------------

## Installation & Compiling from Source

For Windows:
Double-click compile_windows.bat. It will automatically download dependencies, compile the source code
into a standalone .exe, and place it in the 'builds/' folder.

For macOS / Linux:
Open your terminal, navigate to the folder, and run:
chmod +x compile_mac.sh
./compile_mac.sh

-------------------------------------------------------------------------------------------------

## Practitioner FAQ // Pro Tools & DAW Tips

1. "My MIDI markers don't line up with the video!" // The 120 BPM Rule
Your DAW session tempo MUST be set to exactly 120 BPM when you import the MIDI file.
If your session is set to 120 BPM, the markers will be 100% frame-accurate.

2. Session Start Timecode Mismatch
The 'Session Start Timecode' you type into VCut2DAW such as 01:00:00:00 must match your DAW's Session Start Time.

3. The AAF Audio is Offline / Empty?
This is intentional. The tool generates a 'Dummy' AAF track without bulky audio media. Its purpose is
to create empty clips on your timeline so you can use 'Tab to Transient' to jump across scene cuts.

-------------------------------------------------------------------------------------------------

## Collective, Credits & License

Collective         : Xulab Collective // https://github.com/xulab-collective
Founding Architect : Furkan Utku Gercik // @Rhinofug - https://github.com/rhinofug | https://x.com/Rhinofug
Co-Architect       : Muhammed Kol // @Parapazula - https://github.com/Parapazula
Testers            : Caglar "Cakan" Cakmak, Can Dogduaslan, Omur Ozturk, Cagdas Yarman

Licensed under the GNU Affero General Public License v3.0 // AGPLv3. See LICENSE for details.

-------------------------------------------------------------------------------------------------

## Acknowledgments & Open Source Credits

- PySceneDetect // by bcastillox: Frame-analysis and cut detection engine.
- pyaaf2 // by markreidvfx: AAF reading/writing library for Pro Tools integration.
- Mido: MIDI object generation.
- CustomTkinter // by TomSchimansky: Dark-mode desktop GUI framework.
