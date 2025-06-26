# SimCLR

###  Self-Supervised Representation Learning with SimCLR

This project implements SimCLR, a **self-supervised learning** approach for visual representation learning. The model was trained on the Flowers dataset using contrastive loss, achieving a final training loss of **0.4750**, which reflects strong alignment between augmented views of the same image in latent space.

During linear evaluation, a simple classifier trained on top of the frozen encoder achieved a cross-entropy loss of **0.1144**, demonstrating that the learned representations are highly discriminative and effective for downstream classification tasks like flower species recognition.
