Finetuning videos

- https://www.youtube.com/watch?v=eeM6V5aPjhk&pp=ygUSZmluZXR1bmluZyBheG9sb3Rs
- https://www.youtube.com/watch?v=74NSDMvYZ9Y&pp=ygUSZmluZXR1bmluZyBheG9sb3Rs

Dataset
- Start with Orca (https://mlabonne.github.io/blog/notes/Large%20Language%20Models/orca.html). Find the training dataset (dont ask us for it. We expect you to do your own research)
- Removed instructions with less than 100 tokens in response. (NOTE: tokens are not words)
- Data deduplication by doing grouping using cosine similarity (threshold>0.95). You CANNOT use TF-IDF for this purpose.
- Plot a token distribution graph. If you do not create this graph, we will reject the interview.
- publish this dataset on huggingface (https://huggingface.co/docs/datasets/upload_dataset). We will need the link to this dataset.
- Do a finetune of Mistral using this new dataset that you created. If you do not use this new dataset, we will reject the interview. 
- Before doing finetuning, integrate Weights and Biases into ur finetuning (https://docs.wandb.ai/guides/integrations/huggingface) and use it plot loss rates.
- push merged model on Huggingface

# Deadline & instructions. for interview
1. Please do whatever you can and send it within 2 days.  Even if not complete. we will evaluate basis that.
2. Create zip file of notebook code and upload it to google drive. Create a shareable link 
3. Create a demo video using https://www.loom.com/ (**PLEASE PUT YOUR NAME IN THE TITLE OF THE LOOM VIDEO**). We want you to share your desktop screen and walk us through the code and explain what is happening. send us the loom.com demo video link. Please do NOT use any other tool (like google drive, jumpshare, etc etc.). Only Loom.com is acceptable. You can make multiple videos, since the time limit for a video is 5 mins.. 
**WARNING** - in your video, you must actually execute the notebook and show it working. we get a lot of submissions where people have just copy pasted code and are trying to explain it. **If you do not show executing code in your video, we will reject your submission.**

4. **INTERVIEW SUBMISSION** - please send the FOUR links (Google Drive zip file of your code, Huggingface link of your dataset, Huggingface link of your final model and loom) on chat. it will help us track your submission. We will not proceed without these four links.
5. please do NOT upload your code on github under any circumstances.

