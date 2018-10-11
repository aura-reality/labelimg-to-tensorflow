## Installation

### Add tensorflow libraries to PYTHONPATH

https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/installation.md#add-libraries-to-pythonpath

### Install dependencies

This is a smaller set, sufficient for this script, than what's required by `tensorflow/models`

```
virtualenv env
source env/bin/activate
pip install -r requirements.txt
```

### Install protobuf	
	
```
brew install protobuf
```

### Compile tensorflow protobufs

https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/installation.md#protobuf-compilation

## Usage

Accepts three parameters, they take the defaults as given below:

```
python labelimg_to_tf_record.py \
        --images_dir=images \
        --labels_dir=labels \
        --output_path=tfrecord
```
