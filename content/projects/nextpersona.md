---
title: "NextPersona"
date: 2024-10-09
draft: false
ShowToc: true
cover:
  image: "/assets/NextPersona/NextPersona_In_Action.png"
  # can also paste direct link from external site
  # ex. https://i.ibb.co/K0HVPBd/paper-mod-profilemode.png
  alt: "NextPersnona"
  caption: ""
  relative: false # To use relative path for cover image, used in hugo Page-bundles
---

# Introduction
[NextPersona](https://www.nextpersona.com/) is a web application that enables its users to personalize their own digital “persona” and hold conversations with it natively. This application utilizes the large language model GPT-4 by OpenAI, enabling seamless and natural conversational exchanges in multiple languages.

NextPersona is developed in Python, with inspiration from [@avrabyt’s MemoryBot](https://github.com/avrabyt/MemoryBot). Streamlit is chosen as the platform for frontend due to its easy-to-use GUI library and concise documentation. LangChain is utilized as the backend for this app for its capability of integrating multiple AI models, enabling the possibility of easy scaling and expansion in the future.

{{< figure src="/assets/NextPersona/NextPersona_Main_Page.png" caption="Figure 1. NextPersona's main page." >}}

# Customization and Configuration
NextPersona offers users with in-depth configuration features that allows the “persona” to be customized according to the user’s preference. In a single session, configuration parameters can be changed on-the-fly as desired to fine-tune the response from the model.

{{< figure src="/assets/NextPersona/NextPersona_Config_Menu.png" caption="Figure 2. Config menu.">}}

# In Action
During internal testing, NextPersona performed reasonably well in terms of responsiveness and intuitiveness. The average response time is around two to five seconds for moderate-to-long input strings, which simulates realistic human typing time in a causal conversation session.

{{< figure src="/assets/NextPersona/NextPersona_In_Action.png" caption="Figure 3. Screenshot from sample run.">}}

# Next Steps
The current state of this application is a technical preview of the capabilities of the GPT-4 model and the possibility of customizing “virtual friends” through adjustments in the system prompt sent using OpenAI’s API. NextPersona will receive regular updates that will include new features such as user accounts, long-term non-session-based data storage and retrieval, and much more.

# Source Code
NextPersona is fully open source. The source code of this project can be accessed through GitHub [here](https://github.com/ansontsun/nextpersona).