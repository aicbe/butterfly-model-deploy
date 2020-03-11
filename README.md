```console

tensorflow_model_server --model_base_path=/mnt/e/git/butterfly-model-deploy/my_image_classifier --rest_api_port=9000 --model_name=ImageClassifier

cd flask_Server
flask run --host=0.0.0.0
```
