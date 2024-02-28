# AI Training Opt Out
Known tags and settings suggested to opt out of having your content used for AI training.

# Contents

* [**robots.txt**](/robots.txt) A copy-and-paste collection of tags to add to your own robots.txt
* [**meta-tags.html**](/meta-tags.html) A copy-and-paste collection of tags to add to your own `<head>`
* [**headers.txt**](/headers.txt) HTTP headers you can add to your responses. This is more more involved and installation is outside the scope of this document.
* [**ai.txt**](/ai.txt) An alternative to robots.txt created by Spawning, the company behind [haveibeentrained.com](https://haveibeentrained.com/).
* [**ip-ranges.txt**](/ip-ranges.txt) Known IP ranges for AI crawlers. These will change over time, so links to the canonical source is included.
* [**tdmrep.json**](/.well-known/tdmrep.json) A Web protocol, capable of expressing the reservation of rights relative to text & data mining (TDM)

# Other Opt-Outs

* **OpenAI** (Includes ChaGPT and DALL·E): You can opt-out of having your input and output to their services used to train by emailing your organization ID to [support@openai.com](mailto:support@openai.com). *Note: This doesn't include any data they scraped to train their model.*
* **StabilityAI**: Stable Diffusion 3 will honor opt-out requests on [haveibeentrained.com](https://haveibeentrained.com/).
* **AWS**: "AWS may be using your data to train its AI models, and you may have unwittingly consented to it. Prepare to jump through a series of complex hoops to stop it." -- [How to Stop Feeding AWS’s AI With Your Data](https://www.lastweekinaws.com/blog/How-to-Stop-Feeding-AWSs-AI-With-Your-Data/)
* **Substack** "If you do NOT want your publication to be used to train AI, open your publication, go to Settings > Publication details and switch it on."
* **[Wordpress](https://wordpress.com/support/privacy-settings/#prevent-third-party-sharing)** and **[Tumblr](https://help.tumblr.com/hc/en-us/articles/115011611747-Privacy-options#01H692KHGF5N3SVHDV02P5W34P)** are both opt-out for your post content.

# References

* [How to Block ChatGPT From Using Your Website Content](https://www.searchenginejournal.com/how-to-block-chatgpt-from-using-your-website-content/478384/)
* [All Deviations Are Opted Out of AI Datasets](https://www.deviantart.com/team/journal/UPDATE-All-Deviations-Are-Opted-Out-of-AI-Datasets-934500371)
* [OpenAI Terms of Use](https://openai.com/terms/)
* [Stability AI plans to let artists opt out of Stable Diffusion 3 image training](https://arstechnica.com/information-technology/2022/12/stability-ai-plans-to-let-artists-opt-out-of-stable-diffusion-3-image-training/)
* [Stop AI Data Mining in its Tracks with AI.txt](https://site.spawning.ai/spawning-ai-txt)
* [Sites scramble to block ChatGPT web crawler after instructions emerge](https://arstechnica.com/information-technology/2023/08/openai-details-how-to-keep-chatgpt-from-gobbling-up-website-data/)
* [An update on web publisher controls](https://blog.google/technology/ai/an-update-on-web-publisher-controls/) -- Google's VP of Trust
* [Dark Visitors: A List of Known AI Agents on the Internet](https://darkvisitors.com/) 
* [TDM Reservation Protocol (TDMRep)](https://www.w3.org/community/reports/tdmrep/CG-FINAL-tdmrep-20240202/)
