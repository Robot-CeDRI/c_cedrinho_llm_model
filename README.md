```bash
autotrain llm --train
 --project_name CedriTinyLlama
 --model TinyLlama/TinyLlama-1.1B-Chat-v1.0
 --data_path your_data_set 
 --use_peft --use_int4 
 --learning_rate 2e-4 
 --train_batch_size 2 
 --num_train_epochs 3 
 --trainer sft 
 --model_max_length 2048
```