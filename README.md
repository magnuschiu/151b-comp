Ok so due to unfortunate circumstances, we didn't have enough time to run everything our code does, so there are two notebooks. 
One is our theoretical best model. (Will prob go over in final report)
The other was used for fast generation of answers (what we submitted)

To run the theoretical notebook. For the first run, we would switch the dataset to public.jsonl and generate responses after the whole notebook has run, it will have trained the GRPO and LoRA. And now we would run the generation again but now on private.jsonl and it would have our
GRPO and LoRA fine-tuning.  (currently the code is only generating for private.jsonl (no GRPO + LoRA due to time constraints). Converted to run_inference_theoretical.py.

The fast gen notebook has been converted to run_inference.py and can be run as is.

DIRECTORIES NEED TO BE ADJUSTED (THE NOTEBOOKS WERE RUN ON KAGGLE NOTEBOOKS AND ARE A BIT DIFFERENT WITH THE ROOTS AND STUFF) 

i tried my best. its hard given the circumstances, i had.
