# Benchmark for Environment Attacks on Traffic Sign Recognition.
Benchmark videos for testing the robustness of automotive CV Models against Environment Attacks on Traffic sign recognition based on Carla Simulation.

## Description
Collection of videos generated in CARLA that simulate the phantom attack and various adversarial attacks on traffic sign recognition. These videos can be used by researchers or developers for testing the robustness of autonomous driving computer vision models against those attacks.

The Adversarial videos were generated with the CARLA-TSR-adversarial-benchmark tool at https://github.com/FriedrichZimmer/CARLA-TSR-adversarial-benchmark.

## Phantom attack benchmark
This video is having several German speed 60 sign at various locations, that are easily recognized as not being real traffic signs by humans. A CV model for traffic sign detection or segmentation model should not detect any traffic signs in this video.

## Adversarial sign benchmark
These videos are having a single kind of german traffic sign at various locations. A detector or classifier should only be able to detect this sign. There are four signs, which are all recorded with five different camera settings.

- German speed 60 (unmodified)
- German speed 120 (unmodified)
- Adversarial example for a speed 60 sign that is aiming to be misrecognized as speed 120 (Source: Woitschek and Schneider)
- Adversarial example for a speed 120 sign that is aiming to be misrecognized as speed 30 (Source: Sitawarin et al.)