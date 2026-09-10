# @gpuix/react

## 0.6.1

### Patch Changes

- Park spring `motion.div` frame leases at rest so a settled spring stops calling `setCurrent` and no longer rebuilds GPUI every frame. A retarget re-subscribes `onFrame`. Soft GELATIN crawl hard-settles between 280ms and 420ms. Tween `motion.div` is unchanged.
- Add a macOS frosted-glass window example that combines `windowBackground: 'blurred'` with a transparent titlebar and translucent React surfaces.

