### Android development environment for ubuntu 14.04 LTS

* Oracle Java JDK 7
* Android SDK r23
* Gradle 1.13

#### Install

You can either pull from `xzan/docker-android-dev`:

```
docker pull xzan/docker-android-dev
```

```
docker run -i -t xzan/docker-android-dev /bin/bash
```

or add it to your Dockerfile:

```
FROM xzan/docker-android-dev
```

