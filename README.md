# SSD, FSSD, YOLO implemented.

Build:
  ```Shell
  # Modify Makefile.config according to your Caffe installation.
  cp Makefile.config.example Makefile.config
  make -j $(($(nproc) + 1))
  # Make sure to include $CAFFE_ROOT/python to your PYTHONPATH.
  make py
  ```

I use this just to build the caffe environment only.    
The tool for furthur development is [here](http://github.com/miamor/CF_tools)
