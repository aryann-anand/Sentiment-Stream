## HOW TO RUN

Step 1: Clone the repository
```
git clone https://github.com/aryann-anand/Sentiment-Stream.git
```

Step 2: Open the cloned repository and create a conda environment. Activate the new environment
```
conda create -n amazonreview python=3.10
```
```
conda activate amazonreview
```

Step 3: Install the requirements file
```
pip install -r requirements.txt
```

Step 4: Download the test csv file from here ( you can use your own )
```
https://drive.google.com/file/d/1ywE_cy3WKgkoB9w0DuNeelLueEVk_3to/view?usp=sharing
```

Step 5: Run the app
```
flask --app api.py run
```

Step 6: The app will run on port 5000. 
```
localhost:5000
```
