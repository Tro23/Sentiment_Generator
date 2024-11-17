<h1>Custom Sentiment Analysis model</h1>
<br></br>
<p>The model trained and built is a Sentiment Analyser 
that classifies sentiments into 5 categories:
<ul>
<li>"Strong Negative"</li>
<li>"Mild Negative"</li>
<li>"Neutral"</li>
<li>"Mild Positive"</li>
<li>"Strong Positive"</li>
</ul>
</p>
<br></br>
<h3>The Model on HuggingFace</h3>
<p>The link to he model - click <a href="https://huggingface.co/rohittamidapati11/fine_tuned_sentiment_model_rt2">here</a></p>
<br></br>
<h3>How To Run this model?</h3>
<h4>Step1: Setting up The Packages</h4>
<ul>
    <li>Installing 'requirements.txt' file</li>
    <li>
    All the valid dependencies that run smoothly together have been put together. All of them are !pip installable.
    </li>
    <ul>
        <li><pre><code>pip install -r requirements.txt</code></pre></li>
    </ul>
</ul>
<h4>Step2: Generating The Sample Data <sub>(The Api_Key that I generated can be used.)</sub></h4>

<ul>
	<li>Run the .ipynb file called 'Synthetic_Data_Generation.ipynb' under the folder 'Synthetic Data'</li>
	<li>That .ipynb notebook that generates samples using a Llama model, "meta-llama/Llama-3.2-1B-Instruct" will generate three JSON files:
	<ul>
		<li>Training_Dataset.json</li>
		<li>Validation_Dataset.json</li>
		<li>All_Generated_Samples.json</li>
	</ul></li>
</ul>
<h4>Step3: Training the Sentiment Model</h4>
<ul>
	<li>Running the .ipynb notebook, 'Model_Training.ipynb' under the folder 'Model_Training' will generate the model.</li>
	<li>The model uses a pre-trained Roberta model, "IDEA-CCNL/Erlangshen-Roberta-110M-Sentiment", which is under 150M parameters</li>
</ul>
