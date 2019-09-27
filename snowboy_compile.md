## First apt-get install sox, portaudio and its Python binding pyaudio:

sudo apt-get install python-pyaudio python3-pyaudio sox <br />
or <br />
pip install pyaudio

## Compile a supported swig version (3.0.10 or above)

wget http://downloads.sourceforge.net/swig/swig-3.0.10.tar.gz <br />
sudo apt-get install libpcre3 libpcre3-dev <br />

## Permission

For permission on any file " sudo chmod a+x [file directory]

## Then run 

./configure --prefix=/usr                  \ <br />
        --without-clisp                    \ <br />
        --without-maximum-compile-warnings && <br />
make <br />
sudo make install && <br />
sudo install -v -m755 -d /usr/share/doc/swig-3.0.10 && <br />
sudo cp -v -R Doc/* /usr/share/doc/swig-3.0.10 <br />
