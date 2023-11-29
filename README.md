# NLP-Tasks-using-Transformers
<table><tr><th colspan="1"><b>S.No</b> </th><th colspan="1"><b>Application / Downstream Task</b></th><th colspan="1"><b>Model to be tried</b> </th><th colspan="1"><b>Metrics</b> </th></tr>
<tr><td colspan="1">1. </td><td colspan="1" rowspan="5">Text Classification </td><td colspan="1">BERT </td><td colspan="1">Accuracy Score = 0.9174 F1 Score (Micro) = 0.7785 F1 Score (Macro) = 0.6330 </td></tr>
<tr><td colspan="1">2. </td><td colspan="1">DistillBERT </td><td colspan="1">Accuracy Score = 0.9263 F1 Score (Micro) = 0.7877 F1 Score (Macro) = 0.6431 </td></tr>
<tr><td colspan="1">3. </td><td colspan="1">ALBERT </td><td colspan="1">Accuracy Score = 0.9217 F1 Score (Micro) = 0.7431 F1 Score (Macro) = 0.4875 </td></tr>
<tr><td colspan="1">4. </td><td colspan="1">RoBERTa </td><td colspan="1">Accuracy Score = 0.9254 F1 Score (Micro) = 0.7502 F1 Score (Macro) = 0.5614 </td></tr>
<tr><td colspan="1">5. </td><td colspan="1">BART </td><td colspan="1">Accuracy Score = 0.9229 F1 Score (Micro) = 0.7787 F1 Score (Macro) = 0.6379 </td></tr>
<tr><td colspan="1">6. </td><td colspan="1" rowspan="4">Token Classification </td><td colspan="1">BERT </td><td colspan="1"><p>{'eval_loss': 0.2619, </p><p>` `'eval_precision': 0.5926,  'eval_recall': 0.3438, </p><p>` `'eval_f1': 0.4351, </p><p>` `'eval_accuracy': 0.9416,  'eval_runtime': 4.3885, </p><p>` `'eval_samples_per_second': 293.263, </p><p>` `'eval_steps_per_second': 18.457,  'epoch': 2.0} </p></td></tr>
<tr><td colspan="1">7. </td><td colspan="1">DistillBERT </td><td colspan="1"><p>{'eval_loss': 0.2781, </p><p>` `'eval_precision': 0.5695, </p><p>` `'eval_recall': 0.2808, </p><p>` `'eval_f1': 0.3761, </p><p>` `'eval_accuracy': 0.9399, </p><p>` `'eval_runtime': 2.4784, </p><p>` `'eval_samples_per_second': 519.293, </p><p>` `'eval_steps_per_second': 32.683,  'epoch': 2.0} </p></td></tr>
<tr><td colspan="1">8. </td><td colspan="1">ALBERT </td><td colspan="1"><p>{'eval_loss': 0.2514, </p><p>` `'eval_precision': 0.5820, </p><p>` `'eval_recall': 0.3549, </p><p>` `'eval_f1': 0.4409, </p><p>` `'eval_accuracy': 0.9468, </p><p>` `'eval_runtime': 70.2674, </p><p>` `'eval_samples_per_second': 18.316, </p><p>` `'eval_steps_per_second': 1.153,  'epoch': 2.0} </p></td></tr>
<tr><td colspan="1">9. </td><td colspan="1">RoBERTa </td><td colspan="1"><p>{'eval_loss': 0.2272, </p><p>` `'eval_precision': 0.5585,  'eval_recall': 0.4819, </p><p>` `'eval_f1': 0.5174, </p><p>` `'eval_accuracy': 0.9493,  'eval_runtime': 18.2888, </p></td></tr>
</table>

<table><tr><th colspan="1"></th><th colspan="1"></th><th colspan="1"></th><th colspan="1"><p>` `'eval_samples_per_second': 70.371, </p><p>` `'eval_steps_per_second': 4.429,  'epoch': 2.0} </p></th></tr>
<tr><td colspan="1">10. </td><td colspan="1" rowspan="5">Question Answering </td><td colspan="1">BERT </td><td colspan="1">global_step=750, training_loss=1.7336, metrics={'train_runtime': 10433.0395, 'train_samples_per_second': 1.15, 'train_steps_per_second': 0.072, 'total_flos': 2351670810624000.0, 'train_loss': 1.7336, 'epoch': 3.0 </td></tr>
<tr><td colspan="1">11. </td><td colspan="1">RoBERTa </td><td colspan="1">global_step=750, training_loss=0.6353, metrics={'train_runtime': 1012.5891, 'train_samples_per_second': 11.851, 'train_steps_per_second': 0.741, 'total_flos': 2351670810624000.0, 'train_loss': 0.6353, 'epoch': 3.0 </td></tr>
<tr><td colspan="1">12. </td><td colspan="1">T5 </td><td colspan="1">global_step=750, training_loss=4.4234, metrics={'train_runtime': 515.4332, 'train_samples_per_second': 23.281, 'train_steps_per_second': 1.455, 'total_flos': 2351670810624000.0, 'train_loss': 4.4234, 'epoch': 3.0 </td></tr>
<tr><td colspan="1">13. </td><td colspan="1">BigBird (<b>for Extra Work</b>) </td><td colspan="1">global_step=750, training_loss=1.5889, metrics={'train_runtime': 13538.7056, 'train_samples_per_second': 0.886, 'train_steps_per_second': 0.055, 'total_flos': 2482279077888000.0, 'train_loss': 1.5889, 'epoch': 3.0 </td></tr>
<tr><td colspan="1">14. </td><td colspan="1">Longformer (<b>for Extra work</b>) </td><td colspan="1">global_step=8544, training_loss=0.5953, metrics={'train_runtime': 3147.1509, 'train_samples_per_second': 2.715, 'train_steps_per_second': 2.715, 'total_flos': 2092926538137600.0, 'train_loss': 0.5953, 'epoch': 3.0 </td></tr>
<tr><td colspan="1">15. </td><td colspan="1" rowspan="2">Summarization </td><td colspan="1">T5 </td><td colspan="1">global_step=1980, training_loss=2.6152, metrics={'train_runtime': 484.1179, 'train_samples_per_second': 8.172, 'train_steps_per_second': 4.09, 'total_flos': 1070812702310400.0, 'train_loss': 2.6152, 'epoch': 4.0 </td></tr>
<tr><td colspan="1">16. </td><td colspan="1">Pegasus </td><td colspan="1">global_step=1980, training_loss=1.8268, metrics={'train_runtime': 5100.2761, 'train_samples_per_second': 0.776, 'train_steps_per_second': 0.388, 'total_flos': </td></tr>
<tr><td colspan="1"></td><td colspan="1" rowspan="2"></td><td colspan="1"></td><td colspan="1" valign="top">1\.142921441206272e+16, 'train_loss': 1.8268, 'epoch': 4.0 </td></tr>
<tr><td colspan="1">17. </td><td colspan="1">BigBirdPegasus (<b>for Extra Work</b>) </td><td colspan="1">global_step=3956, training_loss=3.3216, metrics={'train_runtime': 10138.6025, 'train_samples_per_second': 0.39, 'train_steps_per_second': 0.39, 'total_flos': 1.1379741713596416e+16, 'train_loss': 3.3216, 'epoch': 4.0 </td></tr>
<tr><td colspan="1">18. </td><td colspan="1">Translation </td><td colspan="1">T5 </td><td colspan="1">global_step=12710, training_loss=1.4878, metrics={'train_runtime': 6596.4761, 'train_samples_per_second': 30.825, 'train_steps_per_second': 1.927, 'total_flos': 2.245214421540864e+16, 'train_loss': 1.4878, 'epoch': 2.0 </td></tr>
</table>

Datasets:  

Text Classification: Jigsaw dataset:[ https://www.kaggle.com/competitions/jigsaw- toxic-comment-classification-challenge/data ](https://www.kaggle.com/competitions/jigsaw-toxic-comment-classification-challenge/data)

Token Classification: wnut dataset from datasets library(wnut = load\_dataset("wnut\_17")) 

Q&A: squad dataset from datasets library (squad = load\_dataset("squad", split="train[:5000]")) 

Summarization: billsum dataset from datasets library (billsum = load\_dataset("billsum", split="ca\_test")) 

Translation: opus books from datasets library (books = load\_dataset("opus\_books", "en-fr")) 

In text classification RoBERTa performed the best among the BERT variants, the trend is followed in token classification and Q&A too. 

Pegasus performed well in the text summarization task when compared to the other models. 
