# Faktory [![Build Status Image](https://github.com/mu-box/microbox-docker-faktory/actions/workflows/ci.yaml/badge.svg)](https://github.com/mu-box/microbox-docker-faktory/actions)

This is an [Faktory](http://contribsys.com/faktory/) Docker image used to launch a [Faktory](http://contribsys.com/faktory/) service on Microbox. To use this image, add a data component to your `boxfile.yml` with the `mubox/faktory` image specified:

```yaml
data.faktory:
  image: mubox/faktory
```

## Faktory Configuration Options
Faktory components are configured in your `boxfile.yml`. All available configuration options are outlined below.

###### Quick Links

#### Overview of Faktory boxfile.yml Settings
```yaml
data.faktory:
  image: mubox/faktory
  config:
```

### Version
When configuring a Faktory service in your Boxfile, can specify which version of Faktory to use. The following version(s) are available:

- 0.7.0

**Note:** Due to version compatibility constraints, Faktory versions cannot be changed after the service is created. To use a different version, you'll have to create a new Faktory service.

#### version
```yaml
# default setting
data.faktory:
  image: mubox/faktory:0.7.0
```

## Help & Support
This is a Faktory Docker image provided by [Microbox](http://microbox.cloud). If you are running into an issue with the image, feel free to [create a new issue on this project](https://github.com/mu-box/microbox-docker-faktory/issues/new).

## License
This project is released under [The MIT License](http://opensource.org/licenses/MIT).
