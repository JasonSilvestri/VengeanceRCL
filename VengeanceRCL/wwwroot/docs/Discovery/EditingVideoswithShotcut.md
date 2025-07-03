# DDE - Official GiveSendGo Fundraiser Video Editor Shotcut - Discovery

**GiveSendGo.com/DDE**

Our `DDE™ Official GiveSendGo.com/DDE Fundraiser Video Editor` Discovery acts as a basic blueprint for `Shotcut`. We use `Shotcut` as the quick and dirty video editor to create videos, because our current laptops can't handle the more modern editors.

---

[`Home`](../../README.md) » [`Introduction`](../ReadMe.md) » [`Get Latest`](../../Official/EditingVideoswithShotcut.md) · · [`« Previous`](./DdeGiveSendGoAiVoices.md) [`Next »`](./DeepDiscovery.md)

---

## **Discovery Variant:**

> [!CAUTION]
> You are currently viewing the **"_Discovery_" _Variant_** of this **VengeanceRCL Project** section. This is not typically created, and is only here to reference the original discovery we performed on this specific information, before evolving content in the way we use it today.
> 
> Most importantly, this content was draft material at the time of creation, and more than likely to have inconsistency in examples, content format, etc.
>
> See, [Get Latest](../../Official/EditingVideoswithShotcut.md) to visit the `official` latest version of this section.

---

## **Overview**

Our **DDE™ (_Deaf, Disabled & Elderly_)** `DDE™ Official GiveSendGo.com/DDE Fundraiser Video Editor` Discovery acts as a basic blueprint for `Shotcut`. We use `Shotcut` as the quick and dirty video editor to create videos, because our current laptops can't handle the more modern editors.

---

### Table of Contents

 - [Overview](#overview)
  - [Prerequisites](#prerequisites)
  - [Corequisites](#corequisites)
  - [New Game Plan: Lightweight, Legacy-Compatible Video Editors (With Face Blur & Green Screen)](#-new-game-plan-lightweight-legacy-compatible-video-editors-with-face-blur--green-screen)
  - [Top Recommendation: Shotcut](#-top-recommendation-shotcut)
  - [Lightweight Alternative: OpenShot](#-lightweight-alternative-openshot)
  - [Niche but Useful: VSDC Free Video Editor](#-niche-but-useful-vsdc-free-video-editor)
    - [Pro Tip (Manual Face Blur Hack):](#-pro-tip-manual-face-blur-hack)
  - [We Are Officially Using Shotcut](#-we-are-officially-using-shotcut)
  - [How to Remove Green Screen in Shotcut](#-how-to-remove-green-screen-in-shotcut)
    - [Goal:](#-goal)
    - [What You Need:](#-what-you-need)
    - [Step-by-Step Instructions](#step-by-step-instructions)
      - [1. Add Both Clips to Timeline](#1-add-both-clips-to-timeline)
      - [2. Apply Chroma Key Filter](#-2-apply-chroma-key-filter)
      - [3. Tune the Keying](#-3-tune-the-keying)
      - [4. Preview the Result](#-4-preview-the-result)
      - [5. Export Your Video](#-5-export-your-video)
    - [Tips for Better Results](#-tips-for-better-results)
  - [How to Blur a Face in Shotcut](#-how-to-blur-a-face-in-shotcut)
  - [Goal:](#-goal)
  - [Step-by-Step: Blur a Face in Shotcut](#step-by-step-blur-a-face-in-shotcut)
    - [What You Need:](#-what-you-need)
    - [1. Add the Same Video Twice to Timeline](#-1-add-the-same-video-twice-to-timeline)
    - [2. Add a Blur Filter to Track V2](#-2-add-a-blur-filter-to-track-v2)
    - [3. Add a Mask to Isolate the Face Area](#-3-add-a-mask-to-isolate-the-face-area)
    - [4. (Optional) Add Keyframes to Follow a Moving Face](#-4-optional-add-keyframes-to-follow-a-moving-face)
    - [5. Preview & Export](#-5-preview--export)
  - [Quick Recap:](#-quick-recap)
  - [Can Shotcut Record Speaker Output (System Audio)?](#-can-shotcut-record-speaker-output-system-audio)
    - [Can Shotcut Record Speaker Output (System Audio)?](#-can-shotcut-record-speaker-output-system-audio)
    - [Workaround Options: How to Record Speaker Output](#-workaround-options-how-to-record-speaker-output)
    - [Option 1: Use OBS Studio (Free)](#-option-1-use-obs-studio-free)
    - [Option 2: Use Audacity with a Loopback Device](#-option-2-use-audacity-with-a-loopback-device)
      - [Step-by-step:](#-step-by-step)
    - [Option 3: Use VB-Audio Cable (Virtual Cable)](#-option-3-use-vb-audio-cable-virtual-cable)
  - [TL;DR Summary](#-tldr-summary)
  - [Create blank (black screen) video with voiceover or speaker output recorded using OBS Studio](#-create-blank-black-screen-video-with-voiceover-or-speaker-output-recorded-using-obs-studio)
    - [Goal:](#-goal)
  - [Step-by-Step: Record Voiceover or Speaker Output with OBS Studio](#step-by-step-record-voiceover-or-speaker-output-with-obs-studio)
    - [1. Open OBS Studio](#-1-open-obs-studio)
    - [2. Set Up a Blank Video Scene](#-2-set-up-a-blank-video-scene)
    - [3. Set Up Audio Inputs in Mixer](#-3-set-up-audio-inputs-in-mixer)
      - [To record your voice:](#-to-record-your-voice)
      - [To record your speaker output:](#-to-record-your-speaker-output)
    - [4. Start Recording](#-4-start-recording)
    - [5. (Optional) Edit in Shotcut](#-5-optional-edit-in-shotcut)
  - [Bonus Tip: Make a Transparent PNG Overlay (e.g. “Now Speaking…”)](#-bonus-tip-make-a-transparent-png-overlay-eg-now-speaking)
  - [Record Audio-Only in OBS Studio (Voiceover or Speaker Output)](#-record-audio-only-in-obs-studio-voiceover-or-speaker-output)
    - [Step-by-Step Instructions](#step-by-step-instructions)
      - [1. Set Up Your Audio Sources](#1--set-up-your-audio-sources)
      - [2. Change Output Format to Audio-Only](#2--change-output-format-to-audio-only)
      - [3. Remove Video Sources (Optional)](#3--remove-video-sources-optional)
      - [4. Start Recording](#4--start-recording)
    - [Bonus Tip: Combine with Audio Filters](#-bonus-tip-combine-with-audio-filters)
  - [Goal:](#-goal)
  - [Step-by-Step: Manual Audio Ducking in Shotcut](#-step-by-step-manual-audio-ducking-in-shotcut)
    - [1. Put Music and Narration on Separate Tracks](#-1-put-music-and-narration-on-separate-tracks)
      - [Setup:](#setup)
    - [2. Select the Music Track & Add Gain/Volume Filter](#-2-select-the-music-track--add-gainvolume-filter)
    - [3. Enable Keyframes to Control Volume Dynamically](#-3-enable-keyframes-to-control-volume-dynamically)
    - [Optional:](#-optional)
  - [Test It:](#-test-it)

---

## **Prerequisites**

Be sure each technology is installed, with proper versioning, if your goal is to install and use the `VengeanceRCL` Project to its fullest potential.

- [Visual Studio (v 17.14.7)](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/Technologies/#visual-studio)
- [.NET Framework (v 9.0.1)](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/Technologies/#net-framework)
- [ASP.NET Core (v 9.0.1)](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/Technologies/#aspnet-core)
- [Node.js (v 20.14.0)](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/Technologies/#node)
- [npm (v 10.8.1)](https://github.com/JasonSilvestri/JSopX.BridgeTooFar/tree/master/JSopX.BridgeTooFar/DocsOpenX/Technologies/#npm)

We use `ElevenLabs` Ultra realistic, supports SSML-like input for tone/pauses in the creation of our AI Narrator Scripts.
 
- [ElevenLabs (v 3)](https://www.elevenlabs.io)

We use `Shotcut` as the quick and dirty video editor to create videos, because our current laptops can't handle the more modern editors.

- [Shotcut (v 24.11.01)](https://shotcut.org/download/)
 
[`Back to Top`](#table-of-contents)

---

## Corequisites

This `DDE GiveSendGo AI Narrator Voice Script` is associated to a [`Storyboard Markers`](../../Discovery/StoryboardMarkers.md) Lifecycle process.

This means that the following documents are also part of the  [`Storyboard Markers`](../../Discovery/StoryboardMarkers.md) Lifecycle process, and should be followed in the order they are listed:

1. [Storyboard Markers](../../Discovery/StoryboardMarkers.md)
2. [Rules of Engagement](../../Discovery/RulesofEngagement.md)
3. [DDE GiveSendGo Viral Exposé Video Script](../../Discovery/ViralExposeVideoScript.md)
4. [DDE GiveSendGo AI Narrator Voice Script](../../Discovery/DdeGiveSendGoAiVoices.md)
5. [DDE GiveSendGo Campaign Sync](../../Discovery/DdeGiveSendGoCampaignSync.md)

[`Back to Top`](#table-of-contents)

---

## 🎯 New Game Plan: Lightweight, Legacy-Compatible Video Editors (With Face Blur & Green Screen)

Here are **tested, low-GPU-requirement editors** that work *without* requiring OpenGL 4.0+, and support:

This is 100% the right mindset — sometimes the smartest move is to stop forcing modern tools onto hardware that simply wasn’t built for it, especially when **OpenGL**, **DirectX 12**, and **GPU acceleration** have become bare minimums.


| Feature           | Must-Haves You're After              |
| ----------------- | ------------------------------------ |
| ✅ Green Screen    | Basic chroma keying support          |
| ✅ Face Blur       | Manual overlays at minimum           |
| ✅ Audio Overlays  | Multi-track timeline + waveform view |
| ✅ Video Overlays  | Layering video clips over each other |
| ✅ No GPU Required | Works without modern OpenGL/DirectX  |

---

## 🥇 Top Recommendation: **Shotcut**

* ✅ **Actively maintained**
* ✅ Built-in **chroma key**, blur, and masking filters
* ✅ **No GPU required** — works well on older systems
* ✅ You can manually keyframe blur over faces
* ✅ Portable version available

> 🔗 [https://shotcut.org/download/](https://shotcut.org/download/)

**Bonus:** Works surprisingly well on integrated graphics. Great for your situation.

---

## 🥈 Lightweight Alternative: **OpenShot**

* ✅ Super simple timeline
* ✅ **Chroma key support**
* ❌ Blur is *limited*, but you can layer a blurred copy on top with a shape mask
* ✅ Easy for basic video overlays

> 🔗 [https://www.openshot.org/download/](https://www.openshot.org/download/)

---

## 🥉 Niche but Useful: **VSDC Free Video Editor**

* ✅ Designed for low-end Windows systems
* ✅ Works without OpenGL acceleration
* ✅ Has **motion tracking**, **face blur**, **green screen**, **masking**
* ❌ UI is clunky, but powerful
* ❗ Free version has everything; Pro adds minor features

> 🔗 [https://www.videosoftdev.com/free-video-editor](https://www.videosoftdev.com/free-video-editor)

---

### 🧠 Pro Tip (Manual Face Blur Hack):

If you’re manually blurring faces:

1. **Duplicate the video track**
2. Add a **blur effect** to the top one
3. Add a **mask (rectangle/circle)** and keyframe its position to follow the face
4. Leave the original (unblurred) video beneath

This works in `Shotcut`, `VSDC`, and others — and doesn’t need tracking.

---


## 🥇 We Are Officially Using Shotcut

* ✅ **Actively maintained**
* ✅ Built-in **chroma key**, blur, and masking filters
* ✅ **No GPU required** — works well on older systems
* ✅ You can manually keyframe blur over faces
* ✅ Portable version available

> 🔗 [https://shotcut.org/download/](https://shotcut.org/download/)

**Bonus:** All editing suggestions below are also in `Shotcut`.

---

## ✅ How to Remove Green Screen in **Shotcut**

### 🎯 Goal:

Overlay a green screen video onto a background (image or video), removing the green so the subject appears naturally over your scene.

---

### 🧰 What You Need:

* A **green screen video** (subject in front of green background)
* A **background image or video** (what goes behind the subject)

---

###  Step-by-Step Instructions

#### 1. **Add Both Clips to Timeline**

1. Open Shotcut
2. Drag your **background clip** into the timeline → this becomes **Track V1**
3. Drag your **green screen video** above it in timeline → Shotcut will prompt to create **Track V2** (do it)

#### 🎨 2. **Apply Chroma Key Filter**

1. Click the **green screen clip** on Track V2 to select it
2. Go to the **Filters** tab (top bar or press `Ctrl+6`)
3. Click the **+** button to add a filter
4. In the filter list, search or scroll to:

   > ✅ **Chroma Key: Simple** or **Chroma Key: Advanced**

---

#### ✏️ 3. **Tune the Keying**

* If using **Chroma Key: Simple**

  * Default color = green → works for most cases
  * Use the **“Distance”** slider to control how much green gets removed
  * Increase it gradually until the background is fully gone, but stop before you eat into the subject

* If using **Chroma Key: Advanced**

  * Manually pick the green color by clicking the color swatch
  * Use the **“Similarity”** and **“Blend”** sliders to fine-tune the edge quality
  * Better if the lighting on your green screen is uneven

---

#### 🎞️ 4. **Preview the Result**

* Use the preview window to check:

  * Subject appears cleanly cut out
  * No weird green edges or ghosting
  * Background on V1 shows properly

---

#### 💾 5. **Export Your Video**

1. Go to **File > Export**
2. Choose a preset like **YouTube > HD 1080p** or similar
3. Click **Export File**, choose your save location, and wait for the render to finish

---

### ✅ Tips for Better Results

* Try to use **well-lit green screen footage**
* Avoid shadows on green background — they make keying harder
* Use **“Chroma Key: Advanced”** if edges look jagged
* Use **“Crop”** or **“Mask: Simple Shape”** filters if you want to isolate areas

---

## ✅ How to Blur a Face in **Shotcut**

Now let’s tackle **face blurring in Shotcut** — it’s very doable even without motion tracking, and I’ll walk you through a simple but effective **manual blur** technique using keyframes and masking.

---

## 🎯 Goal:

Blur a face in a video — either static or moving — by overlaying a blurred copy and masking just the face area.

---

## Step-by-Step: Blur a Face in Shotcut

### 🔧 What You Need:

* A video with a face you want to blur
* Time and patience to manually keyframe if the face moves

---

### ✅ 1. **Add the Same Video Twice to Timeline**

We’ll blur one copy and use a mask to isolate the blur over the face.

1. Open Shotcut and start a **new project**
2. Drag your video to the **Timeline (Track V1)**
3. Drag the **same video again** directly above V1 → Shotcut prompts to create **Track V2**

> Now you have:
>
> * **Track V1** = original, unblurred video
> * **Track V2** = copy we'll blur and mask

---

### 🎨 2. **Add a Blur Filter to Track V2**

1. Select the clip on **Track V2**
2. Go to the **Filters** panel → click **+**
3. Search for and apply the **“Blur: Gaussian”** filter
4. Adjust the blur level until the face is nicely blurred

---

### 🎭 3. **Add a Mask to Isolate the Face Area**

> We’ll mask the blurred video so it only shows over the face.

1. With the **same V2 clip selected**, add another filter:

   * ✅ **“Mask: Simple Shape”**
2. Set:

   * **Shape** = Ellipse (for round faces)
   * **Operation** = **Write On Clear** (important!)
   * Position the shape over the person’s face using **Size** and **Position** sliders

---

### 🎞️ 4. (Optional) Add Keyframes to Follow a Moving Face

If the person is moving around:

1. In the **Mask filter**, click the **keyframe icon** (little stopwatch) next to **Position**
2. Move the playhead forward in small chunks (e.g., 1 second)
3. Reposition the ellipse each time to follow the face
4. Shotcut will interpolate motion between points

This is manual tracking — a little work, but effective.

---

### 🧪 5. Preview & Export

* Play the video to verify the blurred mask follows the face
* Export as usual (`File > Export`) once it looks good

---

## 💡 Quick Recap:

| Step | Action                                                        |
| ---- | ------------------------------------------------------------- |
| 1    | Duplicate the video to two tracks (V1 = normal, V2 = blurred) |
| 2    | Add **Gaussian Blur** to V2                                   |
| 3    | Add **Mask: Simple Shape** to V2 (only blur the face area)    |
| 4    | (Optional) Use **keyframes** to follow face movement          |
| 5    | Export final video                                            |

---

## ✅ Can Shotcut Record Speaker Output (System Audio)? 

Hey! 👋 Great question — and you're absolutely right: Shotcut does have a **VoiceOver** tool built-in. But here’s the honest breakdown:

### 🎯 Can Shotcut Record Speaker Output (System Audio)?

**Not directly.** Shotcut’s **VoiceOver** feature is designed to record from **microphones only** — not your system speakers.

> 🧨 That means you *can’t* natively record:
>
> * YouTube audio
> * Music playing from your speakers
> * Game or app sounds
>   — using Shotcut alone

---

### ✅ Workaround Options: How to Record Speaker Output

Here are your **best options**, depending on what you want to record:

---

### 🥇 Option 1: **Use OBS Studio (Free)**

* **Records system audio and screen/video**
* Save to file and import into Shotcut later
* Very reliable and customizable

🔗 [https://obsproject.com/](https://obsproject.com/)

---

### 🥈 Option 2: **Use Audacity with a Loopback Device**

If you just want **audio recording only**:

#### 🛠️ Step-by-step:

1. Install [**Audacity**](https://www.audacityteam.org/)
2. In **Windows Sound Settings**, enable a “loopback” or “stereo mix” input:

   * Open Sound Settings → Input → Look for:

     * “Stereo Mix” *(Realtek soundcards)*
     * “What U Hear” *(Sound Blaster cards)*
     * “Loopback” *(Some USB audio interfaces)*
3. Select that as the input in Audacity
4. Hit **Record** while playing the speaker output
5. Export the audio and bring it into Shotcut

---

### 🥉 Option 3: **Use VB-Audio Cable (Virtual Cable)**

* Creates a fake audio device that captures all sound
* Route system sound into it
* Record it as if it were a microphone

🔗 [https://vb-audio.com/Cable/](https://vb-audio.com/Cable/)

---

## 🧠 TL;DR Summary

| Goal                   | Tool                   | Shotcut? |
| ---------------------- | ---------------------- | -------- |
| Mic Voiceover Only     | Shotcut                | ✅ Yes    |
| System Audio Recording | OBS Studio             | ❌ No     |
| Audio Only from System | Audacity + Stereo Mix  | ❌ No     |
| Advanced Routing       | VB-Audio Virtual Cable | ❌ No     |


---

## ✅ Create **blank (black screen) video** with **voiceover or speaker output** recorded using **OBS Studio**

Absolutely — let’s walk through creating a **blank video with a voiceover using OBS Studio**, and export it so you can bring it into Shotcut or anywhere else.

---

### 🎯 Goal:

Create a simple **blank (black screen) video** with **voiceover or speaker output** recorded using **OBS Studio**.

---

## #Step-by-Step: Record Voiceover or Speaker Output with OBS Studio

### ✅ 1. **Open OBS Studio**

If you haven’t already:
🔗 [Download OBS Studio](https://obsproject.com/)

---

### 🎬 2. **Set Up a Blank Video Scene**

1. In **Scenes** → click the **+** → name it something like `BlankScene`
2. In **Sources**, click **+** → choose **Color Source**
3. Create a **solid black** (or any color) background

   * Name it: `BlackBG` → click **OK**
   * Set the color to **black** → click **OK**

You now have a blank canvas to record your voice/sound over.

---

### 🎤 3. **Set Up Audio Inputs in Mixer**

#### 👄 To record **your voice**:

* OBS already adds your **Microphone** by default
* If not:

  * Go to **Settings > Audio**
  * Enable **Mic/Auxiliary Audio**
  * Select your microphone device

#### 🔊 To record **your speaker output**:

* Go to **Settings > Audio**
* Under **Desktop Audio**, select:

  * `Default` (usually works), **or**
  * Explicitly choose your **speakers or loopback device**
* If still no sound, enable "Stereo Mix" in Windows Sound Settings

🔊 **You should now see the volume bars moving** under:

* **Mic/Aux** = voice
* **Desktop Audio** = system sounds

---

### ⏺️ 4. **Start Recording**

1. Hit **Start Recording**
2. Speak or play system audio
3. When done, hit **Stop Recording**

OBS saves it (by default) to:

```
C:\Users\YourName\Videos
```

---

### ✂️ 5. (Optional) Edit in Shotcut

1. Open Shotcut
2. Drag the OBS video in
3. Add other video/audio effects if needed (fade, title, etc.)

---

## 🎁 Bonus Tip: Make a Transparent PNG Overlay (e.g. “Now Speaking…”)

Want to add a message or image during voiceover?

1. Create a PNG with text like “Now Speaking...”
2. In OBS:

   * **Sources → + → Image**
   * Load your PNG
   * Position it on top of the black background
   * Optional: animate using **Filters > Scroll** or fade it in/out

---

Yes — 100% possible! You can **record audio-only in OBS Studio**, even though OBS is mainly a video tool. It just takes a small settings tweak so it **outputs an audio file (e.g. `.mp3` or `.wav`) instead of a video file**.

Here’s how to do it:

---

## ✅ Record Audio-Only in OBS Studio (Voiceover or Speaker Output)

---

### Step-by-Step Instructions

#### 1. 🎙️ **Set Up Your Audio Sources**

* Open **OBS Studio**
* In the **Audio Mixer**, make sure:

  * 🎤 **Mic/Aux** is active (for voice recording)
  * 🔊 **Desktop Audio** is active (for system/speaker output)
* You’ll see green volume bars if audio is being detected

---

#### 2. ⚙️ **Change Output Format to Audio-Only**

1. Go to **Settings > Output**
2. Switch to the **Recording** tab
3. Under **Recording Format**, choose:

   * ✅ `.mp3` (good for compressed voice)
   * ✅ `.wav` (uncompressed, higher quality)

> 📌 Note: MP3 requires your OBS installation to support it. If MP3 is not listed, choose WAV.

4. You can also set the **Recording Path** (where your audio file gets saved)

---

#### 3. 🧼 **Remove Video Sources (Optional)**

* In the **Sources** panel, delete anything you don’t need (e.g., no video layer at all)
* This step isn’t required, but it ensures OBS isn’t rendering unnecessary video frames

---

#### 4. ⏺️ **Start Recording**

* Click **Start Recording**
* Speak or play your system sound (or both)
* Click **Stop Recording** when done

Your audio file (MP3/WAV) will appear in your chosen folder — clean and video-free.

---

### ✅ Bonus Tip: Combine with Audio Filters

Go to:

* **Filters → + → Noise Suppression**, **Noise Gate**, or **Gain**
* This can help improve clarity and reduce hum or background noise in your voiceovers

---

Ah, yes — this is a super common pain point when first working with **Shotcut**, because audio ducking (i.e., lowering background music during voiceover) isn't automatic, and volume control isn’t super intuitive at first.

But I’ve got you. Here's the **cleanest way to manually lower (duck) background music under narration** in Shotcut, without duplicate layers or complications.

---

## 🎯 Goal:

* Keep music at full volume when there’s **no narration**
* Lower music volume **during narration**

---

## 🪜 Step-by-Step: Manual Audio Ducking in Shotcut

### ✅ 1. **Put Music and Narration on Separate Tracks**

This makes controlling each volume independently much easier.

#### Setup:

* Track **A1**: Your **background music**
* Track **A2**: Your **voiceover/narration**

Drag them both into place on the timeline and line them up so they sync.

---

### 🔊 2. **Select the Music Track & Add Gain/Volume Filter**

1. Click the **music clip** (Track A1)
2. Go to **Filters** → click the **+**
3. Search for and add:
   ✅ **“Gain/Volume”** filter

---

### 🎛️ 3. **Enable Keyframes to Control Volume Dynamically**

1. In the **Gain/Volume** filter → click the **stopwatch icon** next to the **level** slider (this enables keyframes)

2. Move the playhead to the **moment *before* narration starts**

   * Set volume to **100%**
   * Click the **diamond icon** to place a keyframe

3. Move a few frames **into the narration**

   * Set volume to something like **25%**
   * This creates a fade-down

4. Move to the **end of the narration**

   * Set another keyframe (volume still at **25%**)

5. A few frames later (after narration ends)

   * Add another keyframe and raise volume back to **100%**

✅ Now you’ve created a smooth fade-out and fade-in of the music during narration!

---

### 💡 Optional:

If you want even smoother transitions:

* **Drag keyframes left or right** to lengthen/shorten fades
* You can add more keyframes anytime if narration stops and resumes

---

## 🧪 Test It:

* Hit play in preview
* Music should now dip under the narration and rise back up after

---

## 🛠️ Troubleshooting:

| Issue                 | Fix                                                                                                                      |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------ |
| Keyframes not visible | Make sure you’ve clicked the **Gain/Volume filter**, and enabled keyframes using the stopwatch icon                      |
| Volume doesn’t change | You may have added keyframes to the wrong clip or track — double-check you selected the **music clip** and not narration |
| Can't hear narration  | Check that voiceover volume is loud enough (use its own Gain filter if needed)                                           |

---

Want me to walk you through this live with a mock project? Or help prep a reusable Shotcut `.mlt` template for voice + music projects?

---

[`Home`](../../README.md) » [`Introduction`](../ReadMe.md) » [`Get Latest`](../../Official/EditingVideoswithShotcut.md) ·· [`Back to Top`](#table-of-contents) · [`« Previous`](./DdeGiveSendGoAiVoices.md) [`Next »`](./DeepDiscovery.md)

---

##### Follow Campaign: [www.givesendgo.com/dde](https://www.givesendgo.com/dde)

###### Copyright © 2025 - All Rights Reserved by Jason Silvestri & Scott Hall