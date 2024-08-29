# Monster Channel Manual

This user manual will guide you through the features and functionality of Monster Channel, helping you harness its full potential. From understanding the core controls to exploring advanced techniques, we’re here to ensure you get the most out of your Monster Channel experience. Whether you’re a seasoned pro or just starting your journey in audio production, Monster Channel is your go-to for achieving that larger-than-life sound.

Let’s dive in and unleash the monster in your mix!

## Installation
- - - 
For Mac and Windows, installation is as easy as running the correct installer. 

For Mac, you’ll run `viator-monster-channel-au.pkg` if you use AU plugins or `viator-monster-channel-vst3.pkg` if you use VST3 plugins. 

For Windows, you’ll run `viator-monster-channel-setup.exe`. You’ll get the “Unknown Publisher” warning, but you can bypass it by clicking “More info”. 

For Linux, there’s no installer, you’ll just need to copy the .vst3 file to your local plugin folder.

## Signal Flow
- - - 
The signal flow of Monster Channel consists of three filters and a distortion circuit:
Input → lowpass → highpass → distortion → tone (high shelf) → output

## Main Controls
- - - 
Monster Channel has six controls for controlling the vibe of the saturation. 

1. **Low Cut**: A cutoff control for the pre-saturation highpass filter. Adjust this to manage how much low-end content is driven into the saturation, allowing you to tighten up the bass and prevent muddiness in your mix.

2. **Tone**: A gain control for the post-saturation high shelf filter. Shape the overall brightness of your sound by boosting or reducing the high frequencies, tailoring the tonal character of the saturated signal.

3. **High Cut**: A cutoff control for the pre-saturation lowpass filter. Use this to tame the high frequencies before they hit the saturation stage, ensuring a smoother and cleaner top end in your mix.

4. **Drive**: Controls the amount of input gain into the saturation algorithm. Increasing this will intensify the distortion and generate richer harmonic content, adding warmth and edge to your sound.

5. **Mix**: Balances the saturated signal with the original dry signal. Use this to blend the two, achieving the perfect mix of processed and unprocessed tones.

6. **Output**: Adjusts the volume of the wet (saturated) signal, allowing you to precisely manage gain staging and ensure the overall level fits seamlessly into your mix.

7. **Input**: Adjusts the gain of the incoming signal, allowing you to control how hard the audio is driven into the Monster Channel, setting the stage for saturation and processing.

8. **Output**: Controls the gain of the signal as it exits the Monster Channel, giving you the ability to fine-tune the final output level for optimal balance and integration into your mix.

## Global Controls
- - -
1. **A/B Presets**: Allows you to save and switch between two local snapshots of your current settings. This feature makes it easy to compare different configurations quickly. Selecting either A or B activates the respective preset, and any adjustments made afterward are automatically saved to that snapshot.

2. **Presets**: This is the global preset manager, where you can save your custom plugin states and browse or load factory presets. It provides an easy way to recall your favorite settings or explore new tones.

3. **Stereo Menu**: This menu lets you select the desired processing mode. In **Stereo** mode, the plugin processes and outputs the signal normally, even on mono tracks. **Mono** mode sums the stereo signal to mono for centered processing. **Mid** mode applies the processing exclusively to the mid (center) part of the stereo field, while **Side** mode processes only the side (stereo width) signals.

4. **HQ Menu**: Choose the desired level of oversampling with this menu, ranging from Off to 16x. Higher oversampling rates provide more accurate processing and reduced aliasing at the cost of increased CPU usage.

5. **Power Button**: Toggles the audio processing on or off, allowing you to bypass the plugin without affecting your signal chain.

6. **Info Menu**: Access essential information and resources, including links to support, the user manual, my Discord server, the support email address, and the End User License Agreement (EULA).

## ToolTips
- - -
At the bottom of the plugin interface, you’ll find a dynamic tooltip area. When you hover over a control, this area displays a brief description, providing a quick explanation of the control’s function. The tooltip disappears when you’re no longer hovering over a control, ensuring a clean and uncluttered interface.