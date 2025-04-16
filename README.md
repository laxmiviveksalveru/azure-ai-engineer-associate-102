steps to do 
✅ Step 1: Create Azure AI Studio
Go to Azure AI Studio.

Sign in with your Azure account.

Click “Create a Project” or use an existing one.

✅ Step 2: Create a Compute Instance
In AI Studio, go to the “Compute” tab.

Click “Create compute”.

Set:

Name: e.g., jupyter-vivek

VM Size: Standard_DS11_v2 (or any suitable)

Authentication: SSH password or key

Wait until the status says “Running”.

✅ Step 3: Launch Jupyter Lab
Click on your compute instance once it's ready.

Click “Open in Jupyter Lab”.

You’ll now be inside a full-featured Azure-hosted Jupyter Lab.

✅ Step 4: Create Azure AI Translator Resource
Go to Azure Portal.

Click “Create a resource” → Search for “Translator” → Click Create.

Fill in:

Name: translator-test

Region: westus (or any)

Pricing Tier: F0 (Free) or S1

After deployment, go to the resource.

Collect the following:

✅ Key

✅ Endpoint URL

✅ Region

✅ Step 5: Use SDK in Jupyter Lab
Open a notebook.

Install the SDK (if not already):
