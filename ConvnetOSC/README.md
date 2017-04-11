## ConvnetOSC

Application which sends ConvNet activations as a 4096-bit input vector over OSC.

To compile it from source, you need the addon [ofxCcv](https://github.com/kylemcdonald/ofxCcv).

To change the OSC host, port, and address, edit the `settings_convnet.xml` file in the data folder. By default, it is set to localhost, port 6448, address `/wek/inputs`, which works out of the box with Wekinator.

Also make sure the file `image-net-2012.sqlite3` is inside the data folder. This can be found in ofxCcv or downloaded directly from [here](https://raw.githubusercontent.com/liuliu/ccv/unstable/samples/image-net-2012.sqlite3).