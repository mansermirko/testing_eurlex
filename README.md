# testing_eurlex
<p dir="auto" data-sourcepos="2:1-2:69"><strong>Test su EurLex con utilizzo di BERT e varianti</strong></p>
<p dir="auto" data-sourcepos="2:1-2:69">Codice compatibile all'utilizzo immediato su COLAB<br />I risultati sono aggiornati manualmente.</p>
<p dir="auto" data-sourcepos="2:1-2:69"><strong>SETUP addestramento</strong></p>
<p dir="auto" data-sourcepos="2:1-2:69">GPU_NUMBER=0<br />MODEL_NAME=&lt;model_name&gt;<br />LOWER_CASE='True'<br />BATCH_SIZE=2<br />ACCUMULATION_STEPS=4<br />TASK='eurlex'&nbsp;</p>
<p dir="auto" data-sourcepos="2:1-2:69">--train_epochs=2<br />--learning_rate=3e-5</p>
<p><strong>Modelli utilizzati:</strong></p>
<ul>
<li>bert-base-uncased</li>
<li>roberta-base-uncased</li>
<li>albert-base-v2</li>
<li>microsoft/deberta-base</li>
<li>xlnet-base-uncased</li>
<li>nlpaueb/legal-bert-base-uncased</li>
<li>nlpaueb/legal-bert-small-uncased</li>
<li>zlucia/custom/legalbert</li>
</ul>
<p>&nbsp;</p>
<p><strong>Referenze</strong>: https://github.com/coastalcph/lex-glue</p>
