# tf-serve-example


docker run -it --rm \
    -p 8500:8500 \
    -v "C:\Users\navan\PGP\deploy-tf\clothing-model:/models/clothing-model/1" \
    -e MODEL_NAME=clothing-model \
    tensorflow/serving:2.3.0