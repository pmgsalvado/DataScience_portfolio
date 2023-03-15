<h3>Airline Twitter Sentiment Analysis</h3>
<p>Objective to classify tweets according to their sentiment: negative, neutral, positive.</p>
<p>Tests were made with:</p>
<ul>
  <li>Original Data with text preprocessed</li>
  <li>Original Data with text preprocessed and replacing emoticons with a sentiment word</li>
  <li>Original Data with text preprocessed -> Data Augmentation (*)  to increase the amount of samples for the minority classes</li>
</ul>

<p><b>*</b> Data Augmentation was done via, translating the text from english to french and then back to english</p>

<h4>Text Processing:</h4>
<p>Involved webscraping a list of emoticons from wikipedia (on notebook)</p>
<p>Removing airline and airport codes -> involved webscraping to fetch those codes</p>
<p>Removing Urls</p>
<p>Replace contractions with full representation.</p>
<p>Etc.</p>
