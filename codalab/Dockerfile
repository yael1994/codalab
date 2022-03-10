FROM codalab/default-cpu

ENV BROKER_URL=pyamqp://dadc7810-551d-40a3-9e35-9fa498027934:83e31b41-c12b-4c79-b6ee-6dcf829615c8@codalab.lisn.upsaclay.fr:5671/5dc38d4a-e0e8-4d82-b1d4-c8deccc03664
ENV BROKER_USE_SSL=True

RUN python3 -m pip install -U --no-cache-dir \
      tensorflow==2.6.0 \
      torch==1.8.0 \
      torchvision \
      onnx \
      onnxruntime
