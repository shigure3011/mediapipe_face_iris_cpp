# Face + Iris Landmarks Real-time Detection in C++ (OpenCV + Tensorflow Lite)

## (Note: This guide is for Windows OS, but the code should work fine on other OS)

This project runs on Mediapipe TFLite models without using Mediapipe framework. For more information:
* Face detection: https://google.github.io/mediapipe/solutions/face_detection.html
* Face landmarks: https://google.github.io/mediapipe/solutions/face_mesh.html
* Iris landmarks: https://google.github.io/mediapipe/solutions/iris.html

## :beginner: Requirements:

### Visual Studio 2019

### CMake >= 3.16
<details>
    <summary>How to set CMake compiler options </summary>
    Follow instructions at https://www.40tude.fr/compile-cpp-code-with-vscode-cmake-nmake/
</details>

### OpenCV (for Demo)
<details>
  <summary>How to install</summary>

1. Download and install pre-built binaries at https://sourceforge.net/projects/opencvlibrary/files/4.5.3/opencv-4.5.3-vc14_vc15.exe/download  
2. Add `<opencv-install-folder>/build/x64/vc15/bin` and `<opencv-install-folder>/build/x64/vc15/lib` to PATH.
</details>

### Tensorflow Lite
<details>
  <summary>How to use pre-built library</summary>

1. Download and extract third_party.zip from https://github.com/iwatake2222/InferenceHelper/releases
2. Change `TFLite_PATH` in CMakeLists.txt
3. Add `TFLite_LIBS` to PATH 

</details>

