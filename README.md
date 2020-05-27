# khaiii: go package (cgo wrapper) of khaiii, Kakao Hangul Analyzer III

## build kahiii in ubuntu 20.04

After download(clone) kahiii source;

    $ mkdir build && cd $_
    $ cmake -E env CXXFLAGS="-w" cmake ..
    $ make
    $ sudo make install
    $ sudo ld-config

Install locations:

* header: `/usr/local/include/khaiii/khaiii_api.h`
* library: `/usr/local/lib/libkhaiii.so*`
* resources: `/usr/local/share/khaiii/`

## reference

* Python wrapper: `khaiii/src/main/python/khaiii/khaiii.py`
* [Command cgo](https://golang.org/cmd/cgo/)
* [21세기 세종계획 말뭉치 구축지침](https://ithub.korean.go.kr/user/total/referenceView.do?boardSeq=5&articleSeq=103&boardGb=T&isInsUpd=&boardType=CORPUS)
