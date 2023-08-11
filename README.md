# AI Training Opt Out
Known tags and settings suggested to opt out of having your content used for AI training.

# Contents

* [**robots.txt**](/robots.txt) A copy-and-paste collection of tags to add to your own robots.txt
* [**meta-tags.html**](/meta-tags.html) A copy-and-paste collection of tags to add to your own `<head>`
* [**headers.txt**](/headers.txt) HTTP headers you can add to your responses. This is more more involved and installation is outside the scope of this document.
* [**ai.txt**](/ai.txt) An alternative to robots.txt created by Spawning, the company behind [haveibeentrained.com](https://haveibeentrained.com/).
* [**ip-ranges.txt**](/ip-ranges.txt) Known IP ranges for AI crawlers. These will change over time, so links to the canonical source is included.

# Other Opt-Outs

* **OpenAI** (Includes ChaGPT and DALL·E): You can opt-out of having your input and output to their services used to train by emailing your organization ID to [support@openai.com](mailto:support@openai.com). *Note: This doesn't include any data they scraped to train their model.*
* **StabilityAI**: Stable Diffusion 3 will honor opt-out requests on [haveibeentrained.com](https://haveibeentrained.com/).
* **AWS**: Instead of configuring this setting individually for each AWS account that your organization uses, you can configure an organization policy that enforces your setting choice on all accounts that are members of the organization. See [AI services opt-out policies](https://docs.aws.amazon.com/organizations/latest/userguide/orgs_manage_policies_ai-opt-out.html) 

# References

* [How to Block ChatGPT From Using Your Website Content](https://www.searchenginejournal.com/how-to-block-chatgpt-from-using-your-website-content/478384/)
* [All Deviations Are Opted Out of AI Datasets](https://www.deviantart.com/team/journal/UPDATE-All-Deviations-Are-Opted-Out-of-AI-Datasets-934500371)
* [OpenAI Terms of Use](https://openai.com/terms/)
* [Stability AI plans to let artists opt out of Stable Diffusion 3 image training](https://arstechnica.com/information-technology/2022/12/stability-ai-plans-to-let-artists-opt-out-of-stable-diffusion-3-image-training/)
* [Stop AI Data Mining in its Tracks with AI.txt](https://site.spawning.ai/spawning-ai-txt)
* [Sites scramble to block ChatGPT web crawler after instructions emerge](https://arstechnica.com/information-technology/2023/08/openai-details-how-to-keep-chatgpt-from-gobbling-up-website-data/)