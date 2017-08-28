What is Zulu? ![Zulu Duke in a Box][1]
======================================

Zulu is a widely available binary distribution of OpenJDK. Zulu distributions are fully tested and compatibility verified builds of the latest versions of the OpenJDK 9 EA, 8, 7, and 6 platforms. Zulu is available free of charge for Linux, Windows, and MacOS platforms, with commercial support available upon request.

Zulu is built, tested, supported and made available by Azul Systems.

[www.azul.com/zulu][2]

Tags and `Dockerfile` links
===========================

The Zulu repository azul/zulu-openjdk provides multiple tagged images. The latest Zulu OpenJDK 9 EA, 8, 7, and 6 versions are:

[9ea][55]

[`8u144`, `8`, `latest` (*8u144/Dockerfile*)][38]

[`7u154`, `7`, `latest` (*7u154/Dockerfile*)][23]

[`6u97`, `6`, `latest` (*6u97/Dockerfile*)][10]

Earlier Zulu OpenJDK 8, 7, and 6 releases can be found at:

[8u11][39], [8u20][40], [8u25][41], [8u31][42], [8u40][43], [8u45][44], [8u51][45], [8u60][46], [8u65][47], [8u66][48], [8u72][49], [8u92][50], [8u102][51], [8u112][52], [8u121][53], [8u131][54]

[7u60][24], [7u65][25], [7u72][26], [7u76][27], [7u79][28], [7u80][29], [7u85][30], [7u91][31], [7u95][32], [7u101][33], [7u111][34], [7u121][35], [7u131][36], [7u141][37]

[6u53][11], [6u56][12], [6u59][13], [6u63][14], [6u69][15], [6u73][16], [6u77][17], [6u79][18], [6u83][19], [6u87][20], [6u89][21], [6u93][22]

Usage
=====

This Zulu repository supports multiple versions of OpenJDK-based Java SE JDKs. Zulu versions 9 EA, 8, 7, and 6 are compliant with Java SE 9 EA, Java SE 8, Java SE 7, and Java SE 6, respectively.

For example, you can run a Zulu OpenJDK 9 EA container with the following command:

    docker run -it --rm azul/zulu-openjdk-debian:9ea java -version

You can run a Zulu OpenJDK 8 container with the following command:

    docker run -it --rm azul/zulu-openjdk-debian:8 java -version

Similarly, you can run a Zulu OpenJDK 7 container with the following command:

    docker run -it --rm azul/zulu-openjdk-debian:7 java -version

And you can run a Zulu OpenJDK 6 container with the following command:

    docker run -it --rm azul/zulu-openjdk-debian:6 java -version


  [1]: http://www.azulsystems.com/sites/default/files//ZuluDocker60.gif
  [2]: http://www.azul.com/zulu
  [10]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/debian/6u97-6.17.0.1/Dockerfile
  [11]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/debian/6u53-6.5.0.2/Dockerfile
  [12]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/debian/6u56-6.6.0.1/Dockerfile
  [13]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/debian/6u59-6.7.0.2/Dockerfile
  [14]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/debian/6u63-6.8.0.1/Dockerfile
  [15]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/debian/6u69-6.9.0.3/Dockerfile
  [16]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/debian/6u73-6.10.0.3/Dockerfile
  [17]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/debian/6u77-6.11.0.2/Dockerfile
  [18]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/debian/6u79-6.12.0.2/Dockerfile
  [19]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/debian/6u83-6.13.0.3/Dockerfile
  [20]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/debian/6u87-6.14.0.1/Dockerfile
  [21]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/debian/6u89-6.15.0.1/Dockerfile
  [22]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/debian/6u93-6.16.0.1/Dockerfile
  [23]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/debian/7u154-7.20.0.3/Dockerfile
  [24]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/debian/7u60-7.5.0.1/Dockerfile
  [25]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/debian/7u65-7.6.0.1/Dockerfile
  [26]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/debian/7u72-7.7.0.1/Dockerfile
  [27]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/debian/7u76-7.8.0.3/Dockerfile
  [28]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/debian/7u79-7.9.0.2/Dockerfile
  [29]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/debian/7u80-7.10.0.1/Dockerfile
  [30]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/debian/7u85-7.11.0.3/Dockerfile
  [31]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/debian/7u91-7.12.0.3/Dockerfile
  [32]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/debian/7u95-7.13.0.1/Dockerfile
  [33]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/debian/7u101-7.14.0.5/Dockerfile
  [34]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/debian/7u111-7.15.0.1/Dockerfile
  [35]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/debian/7u121-7.16.0.1/Dockerfile
  [36]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/debian/7u131-7.17.0.5/Dockerfile
  [37]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/debian/7u141-7.18.0.3/Dockerfile
  [38]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/debian/8u144-8.23.0.3/Dockerfile
  [39]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/debian/8u11-8.2.0.1/Dockerfile
  [40]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/debian/8u20-8.3.0.1/Dockerfile
  [41]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/debian/8u25-8.4.0.1/Dockerfile
  [42]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/debian/8u31-8.5.0.1/Dockerfile
  [43]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/debian/8u40-8.6.0.1/Dockerfile
  [44]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/debian/8u45-8.7.0.5/Dockerfile
  [45]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/debian/8u51-8.8.0.3/Dockerfile
  [46]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/debian/8u60-8.9.0.4/Dockerfile
  [47]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/debian/8u65-8.10.0.1/Dockerfile
  [48]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/debian/8u66-8.11.0.1/Dockerfile
  [49]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/debian/8u72-8.13.0.5/Dockerfile
  [50]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/debian/8u92-8.15.0.1/Dockerfile
  [51]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/debian/8u102-8.17.0.3/Dockerfile
  [52]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/debian/8u112-8.19.0.1/Dockerfile
  [53]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/debian/8u121-8.20.0.5/Dockerfile
  [54]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/debian/8u131-8.21.0.1/Dockerfile
  [55]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/debian/9-ea/Dockerfile