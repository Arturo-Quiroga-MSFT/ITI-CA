# Insurance Claims & Accident Reports Processing with Azure OpenAI

## Overview

This repository provides a comprehensive set of demos and notebooks showcasing how to leverage Azure OpenAI models—including GPT-4 Turbo Vision, GPT-4o, and o4-mini—for advanced insurance claims and accident report processing. The examples span image analysis, document understanding, and report generation, illustrating real-world scenarios in the insurance sector.

## Repository Structure

```
pushtorepo.sh
README.md
1_Car damage copilot/
    azure.env
    Car damage Copilot with GPT-4 Turbo Vision.ipynb
    screenshot.jpg
    images/
2_GPT4-Vision and Azure AI enhancements/
    azure.env
    Car report analysis with GPT4-Vision.ipynb
    car_report.jpg
    screenshot.png
3_GPT-4o/
    azure.env
    GPT-4o in Azure OpenAI.pdf
    GPT-4o model with Azure OpenAI.ipynb
    image1.jpg
    ...
4_o4mini/
    Azure OpenAI o4 mini examples.ipynb
    ...
```

### Key Folders & Files

- **1_Car damage copilot/**  
  Contains a notebook demonstrating car damage assessment using GPT-4 Turbo Vision, with sample images and environment configuration for Azure.

- **2_GPT4-Vision and Azure AI enhancements/**  
  Focuses on analyzing car accident reports and images using GPT-4 Vision, highlighting enhancements possible with Azure AI.

- **3_GPT-4o/**  
  Provides examples and documentation for using the GPT-4o model in Azure OpenAI, including a PDF guide and a notebook with image-based scenarios.

- **4_o4mini/**  
  Features advanced examples with the o4-mini model, including predictive maintenance, legal document drafting, and detailed transformer analysis, demonstrating the model's versatility for structured and unstructured data.

- **azure.env**  
  Environment variable files for securely storing Azure OpenAI credentials and endpoints.

- **pushtorepo.sh**  
  Utility script for pushing updates to the repository.

## Use Cases Demonstrated

- **Automated Car Damage Assessment:**  
  Upload accident images and receive structured damage reports, leveraging GPT-4 Turbo Vision for visual understanding.

- **Accident Report Analysis:**  
  Extract key facts, generate summaries, and identify liability from textual and visual accident reports using GPT-4 Vision and GPT-4o.

- **Document Understanding & Drafting:**  
  Generate legal documents (e.g., purchase agreements) and analyze contracts using Azure OpenAI's advanced reasoning capabilities.

- **Predictive Maintenance (o4-mini):**  
  Analyze technical datasets (e.g., transformer diagnostics) to predict failures and recommend maintenance, illustrating the model's application beyond insurance.

## Getting Started

### Prerequisites

- Azure subscription with access to Azure OpenAI Service.
- Python 3.10+ and Jupyter (or VS Code with Jupyter extension).
- Required Python packages (see individual notebook cells for `requirements.txt` or install instructions).
- Set up your Azure OpenAI credentials in the `azure.env` files in each demo folder.

### Running the Notebooks

1. **Clone the repository:**
   ```sh
   git clone <your-repo-url>
   cd <repo-folder>
   ```

2. **Configure Azure credentials:**
   - Edit the `azure.env` file in the relevant demo folder with your Azure OpenAI endpoint and API key.

3. **Install dependencies:**
   - Open the notebook in VS Code or Jupyter.
   - Run the initial setup cells to install required packages.

4. **Run the demo:**
   - Execute cells in the notebooks (e.g., `Car damage Copilot with GPT-4 Turbo Vision.ipynb`) to process sample images or reports.
   - Review outputs, which include structured reports, summaries, and visualizations.

## How It Works

- **Image Analysis:**  
  Upload accident or damage images; the notebook sends them to Azure OpenAI Vision models, which return structured descriptions and damage assessments.

- **Textual Report Processing:**  
  Accident reports or claims are parsed and summarized using GPT-4o or o4-mini, extracting key information for adjusters or legal review.

- **Integration with Azure:**  
  All models are accessed via Azure OpenAI endpoints, ensuring enterprise-grade security and scalability.

## Example Outputs

- **Car Damage Report:**  
  - Detected damage areas (e.g., "front bumper dented, left headlight cracked")
  - Estimated repair cost (if model is fine-tuned)
  - Structured JSON output for downstream processing

- **Accident Summary:**  
  - Parties involved, location, time, and summary of events
  - Liability assessment (if possible)
  - Recommendations for next steps

## Customization

- Replace sample images or reports with your own data to test the models on real cases.
- Modify prompts in the notebooks to tailor outputs for your specific insurance workflow.

## References

- [Azure OpenAI Service Documentation](https://learn.microsoft.com/en-us/azure/ai-services/openai/)
- [OpenAI o4-mini Announcement](https://azure.microsoft.com/en-us/blog/o3-and-o4-mini-unlock-enterprise-agent-workflows-with-next-level-reasoning-ai-with-azure-ai-foundry-and-github/)
- [OpenAI GPT-4o Model](https://openai.com/index/introducing-o3-and-o4-mini/)

## License

This repository is for demonstration and educational purposes. Please review and comply with Azure OpenAI Service terms of use.

---

For questions or contributions, please open an issue or submit a
