# ofxMosaicPlugin

An ofxVisualProgramming specific code reduction for optimizing Mosaic plugins compile time and binary size

## DEPENDENCIES

openFrameworks 0.12.0

- ofxOsc
- ofxXmlSettings

- ofxAudioFile  **-- FORK**
- ofxImGui      **-- FORK**
- ofxMidi
- ofxPDSP       **-- FORK**


```bash

cd <your_openframeworks_release_folder>/addons

git clone https://github.com/d3cod3/ofxAudioFile
git clone https://github.com/d3cod3/ofxImGui
git clone https://github.com/danomatika/ofxMidi
git clone https://github.com/d3cod3/ofxPDSP

```

Then clone ofxMosaicPlugin

```bash

git clone https://github.com/d3cod3/ofxMosaicPlugin
git submodule init
git submodule update

```

## WRITING PLUGINS

Check the README inside the example
