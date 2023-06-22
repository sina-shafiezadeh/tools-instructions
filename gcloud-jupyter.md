
# Take away commands:
- command 1
- command 2
- command 3
---
## 1. Create a new virtual machine
1.1. Go to your "Compute Engine" dashboard in "Google Cloud" and select the desired project.

1.2. Click on "CREATE INSTANCE".

<img src="images-are-used/gcloud-jupyter/1.png" alt="Image Description" width="648" height="243">

1.3. Define your virtual machine's name that is distinguishable from others.

1.4. Select a "region" for the virtual machine. As a user from Europe, preferably choose a region from Europe to have a faster connection in the future. Here, we have selected "europe-west4 (Netherlands)".

<img src="images-are-used/gcloud-jupyter/2.png" alt="Image Description" width="648" height="243">

1.5. Under the "Machine configuration" section, click on the "GPUs" tab.

1.6. Select "GPU type". Here we selected the "NVIDIA A100 40GB".

<img src="images-are-used/gcloud-jupyter/3.png" alt="Image Description" width="648" height="243">

1.7. Under the "Boot disk" section, click on the "CHANGE" button.

1.8. Select the "Operating system". Here we need to select "Deep Learning on Linux".

1.9. Select "Version". Here we need to select "Debian 11 based Deep Learning VM with M109"

1.10. Specify the "Size (GB)". Here we need to specify "100".

1.11. Click on the "Select" button to save and exist.

<img src="images-are-used/gcloud-jupyter/4.png" alt="Image Description" width="1121" height="638">


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
