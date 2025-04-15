cd submodules
git clone --no-checkout https://github.com/MicrosoftDocs/azure-ai-docs.git
cd azure-ai-docs
git sparse-checkout init
git sparse-checkout set articles/ai-services/openai/includes
git checkout main