Case1: 
✅ Change doc_stride to 75
<img width="807" alt="Screenshot 2025-07-06 at 10 25 10 PM" src="https://github.com/user-attachments/assets/cf4d3d40-c81b-4f00-b75b-81d5b72aa293" />


Case2: 
✅ Dataset preprocessing (position bias prevention)
✅ Hyperparameter tuning (doc_stride)
✅ Postprocessing fixes (empty answer elimination)
✅ Apply Linear Learning Rate Decay

<img width="804" alt="Screenshot 2025-07-06 at 11 34 08 PM" src="https://github.com/user-attachments/assets/8b5e2631-0ef7-4705-94dd-50dfb5e5916e" />

Case3:
✅ get_cosine_schedule_with_warmup
✅ Change doc_stride to 50
✅ max_paragraph_len = 300
<img width="958" alt="Screenshot 2025-07-07 at 12 19 38 AM" src="https://github.com/user-attachments/assets/8bd815cb-50af-4989-be7e-054b6d989884" />


Case4:
✅ Automatic mixed precision
✅ Gradient accumulation
<img width="1122" alt="Screenshot 2025-07-07 at 12 53 12 AM" src="https://github.com/user-attachments/assets/bff0e436-7129-45ad-aa93-23254c3cb4b6" />
