# STECocoapodsDebug

## Abstract

This project is a total repository of some sub projects.

- [CocoaPods](https://github.com/CocoaPods/CocoaPods.git)
- [cocoapods-bin](https://github.com/tripleCC/cocoapods-bin.git)
- [cocoapods-libstcx](https://github.com/STTechnology5652/cocoapods-libstcx.git)
- [STPodTemplate](https://github.com/STTechnology5652/STPodTemplate.git)
- [pod-template](https://github.com/CocoaPods/pod-template.git)

## Use release

The production is release to gemsource, you can use the production by the following command.

- install
  
  ```shell
    gem install cocoapods-libstcx --verbose
  ```

- test
  
  ```shell
  pod --help
  ```

- command help

```shell
pod libstcx --help
pod libstcx create  --help
pod libstcx update-template --help
```

## Using

Use RubyMine to run this project.

- clone project

```shell
git clone https://github.com/STTechnology5652/STECocoapodsDebug.git --verbose
```

- clone submodule

```shell
git submodule init
git submodule sync
git submodule update
```

- prepare environment

```shell
rvm install "ruby-2.7.5" --verbose
bundle install --verbose
```

- open RubyMine

![img](docs/rubymineWindow.png)