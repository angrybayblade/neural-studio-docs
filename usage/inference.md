# Inference

Inference engine provides an easy to use UI to use your trained model on new data.

![5.1 Inference Engine](../.gitbook/assets/5.1.png)

When you upload the image the engine will automatically predict and visualize the output.

![5.2 Inference Result](../.gitbook/assets/5.2.png)

You can also access the inference API using the deployment toolkit. For example, with this example you can perform inference using tools such as CURL.

```text
$  curl -X POST \
   -F "image=@/Users/test.jpg" \
   http://localhost:8000/api/infer
```

