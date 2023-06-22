
# Take away commands:
- command 1
- command 2
- command 3
---
## 1. Create a new virtual machine
1.1. Go to your "Compute Engine" dashboard in "Google Cloud" and select the desired project.

1.2. Click on "CREATE INSTANCE".

<img src="images-are-used/gcloud-jupyter/1.png" alt="Image Description" width="720" height="270">

1.3. Define your virtual machine's name that is distinguishable from others.

1.4. Select a "region" for the virtual machine. As a user from Europe, preferably choose a region from Europe to have a faster connection in the future. Here, we have selected "europe-west4 (Netherlands)".

<img src="images-are-used/gcloud-jupyter/2.png" alt="Image Description" width="720" height="270">

1.5. Under the "Machine configuration" section, click on the "GPUs" tab.

1.6. Select "GPU type". Here we selected the "NVIDIA A100 40GB".

<img src="images-are-used/gcloud-jupyter/3.png" alt="Image Description" width="720" height="270">





```python
def greet(name):
    print("Hello, " + name + "!")

greet("Alice")
```

```bash
$ git clone https://github.com/username/repo.git
$ cd repo
$ ls -la
```
