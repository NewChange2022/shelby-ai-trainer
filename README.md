I am building **Shelby-AI Trainer**: a decentralized AI training and inference platform that uses Shelby as the primary blob storage layer for massive datasets (images, video, text) and model checkpoints.

The application will:
- Read training/inference data at full speed through the **Shelby TypeScript SDK**, leveraging Shelby’s **dedicated private fiber network** to eliminate public internet bottlenecks.
- Take advantage of **erasure coding** to minimize recovery bandwidth and the **paid-read incentive model** to ensure storage providers always deliver maximum performance.
- Use **Aptos Smart Contracts** for automatic auditing, payment channels, and data integrity enforcement.

Expected outcome: Train or run inference on large LLMs or computer-vision models **3–5× faster and cheaper** than traditional cloud storage, while remaining fully decentralized and user-controlled.

MVP will be completed in the next 2 weeks using Python + Shelby SDK + Hugging Face Transformers, starting with a 1 TB image-classification dataset.

Excited to build on Shelby and contribute to the ecosystem! 🚀
