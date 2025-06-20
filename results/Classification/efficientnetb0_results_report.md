## Training Summary

The model was trained over the course of **20 epochs**. The training duration exceeded initial expectations.  
To address this issue, **early stopping** was applied to optimize the training process.

During training:
- The model’s **training accuracy** increased significantly from **81.6%** at the beginning to **91.5%** in the final epoch.
- The **validation accuracy** also improved, rising from **83.3%** to **88.4%**.

These results indicate that the model fit the training data well and was able to generalize effectively to the validation data.

Additionally, the **loss values** decreased substantially throughout the training:
- **Training loss** dropped from **0.4071** to **0.2062** by the 20th epoch.
- **Validation loss** decreased from **0.3968** to **0.3361**.

These improvements demonstrate that both the **accuracy** and **loss** of the model were successfully optimized during training.

## Final Evaluation Metrics

- **F1 Score**: `0.9435`  
- **Accuracy**: `0.9330`  
- **Loss**: `0.1848`
