
### How to build and tag a local image


```
$ uname -a
Linux bazhost 5.13.0-35-generic #40~20.04.1-Ubuntu SMP Mon Mar 7 09:18:32 UTC 2022 x86_64 x86_64 x86_64 GNU/Linux


$ docker build \
        --build-arg MODEL_NAME="sentence-transformers/multi-qa-MiniLM-L6-cos-v1" \
        --tag "twizzler-labs/transformers-inference:sentence-transformers-multi-qa-MiniLM-L6-cos-v1-cuda11.3" \
        .

```
