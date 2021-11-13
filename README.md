# NeBulaWebClient

NeBula is a distributed online shopping system, which is a coursework of the course *Distributed Systems*, developed by a group of students of LUC@BJTU.

The name is given due to the name of the IDE designated by the professor, NetBeans, which could be simply noted as NB. We wanted to achieve a similar effect, and NeBula seems to be a good name.

This repository contains the web client of NeBula. Some of the interfaces are shown as follows.

![Login](https://github.com/V1ctorL/NeBulaWebClient/blob/main/web/assets/images/demo/WechatIMG6532.png)

![Home](https://github.com/V1ctorL/NeBulaWebClient/blob/main/web/assets/images/demo/WechatIMG6535.png)

![Products](https://github.com/V1ctorL/NeBulaWebClient/blob/main/web/assets/images/demo/WechatIMG6539.png)

![Cart](https://github.com/V1ctorL/NeBulaWebClient/blob/main/web/assets/images/demo/WechatIMG6581.png)

![Checkout](https://github.com/V1ctorL/NeBulaWebClient/blob/main/web/assets/images/demo/WechatIMG6583.png)

![Order](https://github.com/V1ctorL/NeBulaWebClient/blob/main/web/assets/images/demo/WechatIMG6582.png)

![ContactUs](https://github.com/V1ctorL/NeBulaWebClient/blob/main/web/assets/images/demo/WechatIMG6546.png)



There are also a [backend server](https://github.com/V1ctorL/NeBula) and a [starter](https://github.com/V1ctorL/NeBulaStarter).

## Install

You can get each part of the code via the related commends.

**The Backend Services**

```shell
git clone git@github.com:V1ctorL/NeBula.git
```

**The Web Client**

```shell
git clone git@github.com:V1ctorL/NeBulaWebClient.git
```

**The Starter**

```shell
git clone git@github.com:V1ctorL/NeBulaStarter.git
```

## Usage

You can run the projects which your preferred IDE. Since they are developed with NetBeans, it is a recommended one.

You can also take a view of the web pages by opening the HTML files in a browser. However, some functions may not be working in this case.

This project provides a SOAP service for [the starter](https://github.com/V1ctorL/NeBulaStarter) to test the network latency. If you want to deploy this project on multiple machines, SOAP services with the same name in the same package will cause a conflict. Hence you should do some refactors for each instance:

- Rename the file name `Pong1.java` to be a new one - e.g., `Pong2.java`.
- Rename the class  `Pong1` to be a new one - e.g., `Pong2`.
- Refactor the annotation of the class - e.g., `@WebService(serviceName = "Pong2")`.

