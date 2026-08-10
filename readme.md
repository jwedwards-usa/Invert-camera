# Backstage Slide Camera

A tiny browser camera for photographing rear-projected slides from backstage.

**Live app:** https://jwedwards-usa.github.io/Invert-camera/

## How it works

1. Open the page and allow camera access.
2. Aim at the back of the projection screen.
3. Pinch the live camera if you need to zoom.
4. Tap **Capture & save slide**.
5. Optionally tap **Crop last slide**, adjust the crop box, and save a cropped copy.

The app flips the image left-to-right so the saved slide reads normally. It prefers the rear/environment camera, keeps camera switching out of the way unless needed, and can also correct an existing mirrored photo from **More options**.

### Zoom

Pinch with two fingers on the live camera. When the browser exposes the phone camera's native zoom, the app uses it. Otherwise it uses a centered digital zoom. Tap the zoom indicator in the top-right corner to reset.

### Crop

Every normal capture is still saved immediately. Cropping is optional afterward: move the crop box, drag its corners, then tap **Crop & save copy**. This keeps the original capture and saves a second cropped image.

No account, upload, or server processing is required; the camera image stays in your browser and saves directly to your device.
