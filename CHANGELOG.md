# v1.7.2
- Added `A` Animated Tag to the `Lighting Multiplier` on each of Blu's Shading Setups.

# v1.7.1
- Added `9.0/AudioLink/Musical Glitter`, a pretty neat Glitter AudioLink Preset with an example Shape Texture. By default, it scales the Size Mod with the `High Mid` and drives Chrono Sparkle Speed with the `Bass` band.

# v1.7.0
- Changed `9.0/Shading/Blu's Shading Setup v6.0` and `9.0/Shading/Blu's Shading Setup v6.0 Outlines Combo` presets to my latest updated setup. Major version increment.
- Updated `9.0/Shading/Smoothed Mayu Style` preset.

# v1.6.2
- Re-marked some properties as Preset on `9.0/Shading/Sacred's Realistic` that I somehow forgot to do.

# v1.6.1
- Added `9.0/Shading/Sacred's Realistic`, reflecting the Wrapped Shading setup that is similar to how Sacred sets it up.

# v1.6.0
- Changed `9.0/Shading/Blu's Shading Setup v6.0` and `9.0/Shading/Blu's Shading Setup v6.0 Outlines Combo` to my latest updated setup.
    - This increment to v1.6 is a self-note to indicate the major changes I made to my personal Shading settings.

# v1.5.5
- Added `9.0/Shading/Smoothed Mayu Style`, a more smoothed version of `Mayu Style`.

# v1.5.4
- Updated some Presets to current.

# v1.5.3
- Added `9.0/Special FX/Glasses Lens`.
- Adjusted `9.0/AudioLink/Outline Color Change Hue` to also include the Color Shift as well, because why not. It looks cool!
- Renamed `9.0/Special FX/Emission/Glowy Sweet Spot` to `9.0/Special FX/Glowy Sweet Spot [Emission]`.
- Fixed `9.0/Shading/Blu's Shading Setup v5.0 Outlines` to stop including the Outline Size from being applied.

# v1.5.2
- Added `9.0/Shading/Mayu Style` which is a unique Multilayer Math Shading Preset. In addition, it uses a neat Skin-like Matcap, Environmental Rim, and Proximity Color. This shading style is heavily inspired by the shading setup used on the Mayu Avatar Base by AzukiTiger (go support them by buying the Avatar!).
- Fixed the included Fallback Cubemap not using Specular Convolution and Trilinear Filtering Mode. The Fallback should now look correct.

# v1.5.1
- Nothing. Just updated the Package Display Name to reflect the BluWizard LABS branding.

# v1.5.0
## MAJOR UPDATE! PLEASE UPGRADE TO POIYOMI TOON SHADER VERSION 9.0 IN ORDER FOR ALL PRESETS TO UPDATE CORRECTLY!

- Added support for Poiyomi Toon v9.0 with fresh new presets, some of which are exclusive to 9.0!
    - `9.0/AudioLink/Outline Glow & Color Change` is exactly what it sounds like. You can now make your Outlines do some awesome AudioLink magic in 9.0! For demonstration purposes, this Preset will change the color to Blue and pulse the Outline Emission when the Bass hits (you can change this if you want). Try it out!
    - `9.0/AudioLink/Bass Wave [Rim Lighting 1]` enables a fun Rim Lighting effect that will increase in width with Emission when the Bass hits.
    - `9.0/Quick Fixes/Enable Lighting in Mirrors` will enable a simple checkmark that fixes an issue where your Avatar's Lighting does not appear correctly in VRChat Mirrors.
    - `9.0/Shading/Toon Cel Style` is the sequel to `Anime Style Redux`. Cel Shading for Poiyomi Toon Shader!
- Reorganized all Preset Names to indicate which Poiyomi versions the Presets support. They are now sorted under `BluWizard's Presets/8.1` and `BluWizard's Presets/9.0` respectively.
- Fixed `9.0/Shading/Blu's Shading Setup` having no Point Light Passthrough.

*Most, if not all, of the previous Presets I've created have been ported with 9.0 Compatibility. However, I cannot guarantee any Presets that were made for 8.1 will apply correctly on 9.0. So I highly recommend using the new 9.0 Presets instead!*

# v1.3.6
- Fixed `Shading/Fake Realistic` with readjustments to the Wrapped Shading. It should be a lot better now.

*NOTE: Since Poiyomi v9.0 is right around the corner, the next updates to Blu's Poiyomi Presets from this point on (v2.x) will include Presets that only specifically support Poiyomi v9.0. Therefore, no more Presets will be added for v8.1.*

# v1.3.5
- Added `Shading/Sacred's Realistic Perfection` Preset. Say a big thanks to Sacred for discovering this absolutely-perfect Realistic Shading setup.

# v1.3.4
- Disabled `Vertex lights (Non-Important)` and `Pixel lights (Important)` on the Preset, `Special FX/GrabPass (Requires Poiyomi Grab Pass)/Glasses with Refraction`.
    - This fixes an issue where Realtime Light Sources, such as Point Lights, would cause the Material to get fogged.

# v1.3.3
- Readjusted `Special FX/Emission/Glowy Sweet Spot` to further reflect my intended look.

# v1.3.2
- Emission Presets will no longer touch `Post Processing -> PP Animations` since they are supposed to be animated by the user. Sorry about that!

# v1.3.1
- Some properties on some Shading Presets were configured incorrectly, so they were fixed. Sorry about that!

# v1.3.0
## REBUILD YOUR PRESETS CACHE FOR THIS RELEASE!! To do this, click `Thry -> Presets -> Rebuild Cache` in the Unity Menu Bar.

- Added `Shading/Anime Style Redux`, a hybrid Cartoon Rim Lighting styled Shading Preset. If you play Genshin Impact or similar Anime-styled games, this Preset might look familiar to you.
- Added `For World Creators/Emulate Standard Shader`. This Preset will directly emulate the shading properties similar to Unity's Standard Shader, for those who wish to use Poiyomi World's features in World Projects.
- Changed the category `Patches` to `Quick Fixes` since that makes a bit more sense to me.
- Changed the category `Special FX/Grab Pass` to `Special FX/Grab Pass (Requires Poiyomi Grab Pass)`, just in case the user didn't know the Preset required using the Poyiomi Grab Pass variant (and a subtle reminder that Grab Pass is now available in the Free version).
- Updated README.md.

# v1.2.2
- Changed `Shading/Blu's Shading Setup` to reflect my latest settings.
- Fixed `Shading/Faint Eye Reflection [Clear Coat]` from not having the correct Preset tags. It should work now!
- Fixed incorrect properties on `Shading/Toon Gradient` Preset.

# v1.2.1
- Added Glasses Refraction preset. best suited for glasses. Uses Poiyomi Grab Pass, so use it wisely!
- Added a Preset enabling cool AudioLink Spectrum Bars. I think it looks wicked!

# v1.2.0
- Added my personal Shading Setup as a Preset, because why not.
- Updated README.md.

# v1.1.0
- Added Basic Dissolve AudioLink Preset.

# v1.0.1
- Added context to README.md.

# v1.0.0
- Initial Release.
