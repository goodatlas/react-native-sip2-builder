# react-native-sip2-builder
A [PJSIP](https://www.pjsip.org) module for React Native with OpenSSL, OpenH264, Opus and G.729

Based on [telefon-one/react-native-sip2-builder](https://github.com/telefon-one/react-native-sip2-builder)


## Versions
| Library              | Version |
|----------------------|---------|
| Android API          | >23-30  |
| Android NDK          | r18b    |
| PJSIP                | 2.9     |
| OPENSSL              | 1.0.2s  |
| OPENH264             | 2.1.1   | 
| OPUS                 | 1.3.1   |
| SWIG                 | 3.0.12  |

## Defined options
```
#define PJMEDIA_AUDIO_DEV_HAS_ANDROID_JNI 0
#define PJMEDIA_HAS_WEBRTC_AEC 1
#define PJMEDIA_HAS_SPEEX_AEC 1
#define PJMEDIA_SPEEX_AEC_USE_AGC 1
#define PJMEDIA_SPEEX_AEC_USE_DENOISE 1
#define PJMEDIA_HAS_OPUS_CODEC 1
```

overwrite `/pjsip/third_party/build/speex/config.h` for speex to operate in floating-point


## Build for Android
```
git clone https://github.com/goodatlas/react-native-sip2-builder
cd react-native-sip2-builder
./build_android.sh
```

## Build for iOS
```
TODO:
```
