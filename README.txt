======================================================================
IMAGE DENOISING WITH DDIM - RESULTS PACKAGE
======================================================================
Generated: 2025-11-08 06:05:46

CONTENTS:
----------------------------------------------------------------------

1. Models/
   - denoising_model_final.pt: Final trained model
   - best_model.pt: Best model during training

2. Visualizations/
   - denoising_results_final.png: Denoising results visualization
   - training_loss_final.png: Training loss curve
   - project_summary_dashboard.png: Summary dashboard

3. Checkpoints/
   - model_epoch_*.pt: Checkpoints from training

4. Reports/
   - project_report.txt: Detailed project report

======================================================================
HOW TO USE:
======================================================================

To load the model:
```python
import torch
model = ImprovedDenoisingUNet()
model.load_state_dict(torch.load('Models/denoising_model_final.pt'))
model.eval()
```

Files included: 3
Files not found: 3
