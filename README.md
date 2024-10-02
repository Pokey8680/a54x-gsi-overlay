# magisk-gsi-overlay
Magisk module to inject overlays for PHH-Treble GSI images

# Inject your own overlay
1. Download this entire repo as a zip
2. Extract the zip content somewhere
3. Replace `system/product/overlay` contents with your own overlays
4. Modify `build.prop` as needed
5. Zip the entire thing back with `zip -r9 module.zip * -x .git README.md **placeholder`
6. Push the `module.zip` to your phone & flash
