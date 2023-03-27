<a href="https://margelo.io">
  <img src="./docs/static/img/banner.svg" width="100%" />
</a>

<h1 align="center">React Camera </h1>



### Documentation

* [Guides](https://react-native-vision-camera.com/docs/guides)
* [API](https://react-native-vision-camera.com/docs/api)
* [Example](./example/)

### Features

* Photo, Video and Snapshot capture
* Customizable devices and multi-cameras (smoothly zoom out to "fish-eye" camera)
* Customizable FPS
* [Frame Processors](https://react-native-vision-camera.com/docs/guides/frame-processors) (JS worklets to run QR-Code scanning, facial recognition, AI object detection, realtime video chats, ...)
* Smooth zooming (Reanimated)
* Fast pause and resume
* HDR & Night modes

> See the [example](./example/) app

### Example

```tsx
function App() {
  const devices = useCameraDevices('wide-angle-camera')
  const device = devices.back

  if (device == null) return <LoadingView />
  return (
    <Camera
      style={StyleSheet.absoluteFill}
      device={device}
      isActive={true}
    />
  )
}
```

### Adopting at scale


####  Get started by [setting up permissions](https://react-native-vision-camera.com/docs/guides/)!
# React Camera
