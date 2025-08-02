#  Generalized Anxiety Self-Assessment and Relaxation Guidance Chatbot

##  **IMPORTANT: NOT FOR MEDICAL DIAGNOSIS**

**THIS CHATBOT IS FOR EDUCATIONAL PURPOSES ONLY AND DOES NOT PROVIDE MEDICAL DIAGNOSES, TREATMENT, OR REPLACE PROFESSIONAL HEALTHCARE.**

If you are experiencing severe anxiety, panic attacks, or thoughts of self-harm, please contact a healthcare provider immediately or call:
- **Emergency: 911**
- **Nova Scotia Mental Health Crisis Line: 1-888-429-8167**
- **Kids Help Phone: 1-800-668-6868**

---

##  Project Overview

This educational chatbot provides anxiety self-assessment tools and evidence-based relaxation techniques for residents of Halifax, Nova Scotia. Built using the Ollama + AnythingLLM stack, the system leverages authoritative Canadian health resources to help users understand anxiety symptoms and learn effective coping strategies.

The chatbot is designed as an educational research project and serves as a bridge between self-help resources and professional mental healthcare services.

##  Key Features

- ** Self-Assessment Guidance**: Educational support using validated tools like GAD-7
- ** Relaxation Techniques**: Step-by-step instruction for evidence-based stress management
- ** Evidence-Based Resources**: Content from Nova Scotia Health, Health Canada, and CMHA
- ** Crisis Resource Access**: Immediate access to local Halifax/Nova Scotia emergency contacts
- ** Professional Referral Guidance**: Clear direction on when to seek professional help
- ** Ethical Safeguards**: Built-in disclaimers and scope limitations

##  Core Capabilities

The chatbot can help users with:

1. **"I keep worrying about everything—is this anxiety?"**
   - Educational information about anxiety symptoms
   - Guidance through self-assessment tools
   - Understanding when to seek professional help

2. **"Can you teach me a simple relaxation exercise?"**
   - Evidence-based relaxation techniques
   - Step-by-step instruction and practice guidance
   - Scientific background on stress management methods

##  Technology Stack

- **Local LLM**: Ollama
- **RAG Framework**: AnythingLLM
- **Knowledge Base**: PDF, Markdown, and text documents
- **Sources**: Nova Scotia Health, Health Canada, CMHA resources

##  Repository Structure

```
/anxiety-chatbot
├── knowledge_base/
│   ├── knowledge_document_1.pdf     # GAD-7 Assessment Tool
│   ├── knowledge_document_2.md      # Nova Scotia Health Resources
│   └── knowledge_document_3.txt     # CMHA Anxiety Self-Help Guide
├── prompt/
│   └── system_prompt.txt            # Chatbot system configuration
├── documentation/
│   ├── scenario_pack.md             # Project requirements (provided)
│   └── use_case_description.md      # User needs and success criteria
├── demo/
│   ├── demo_video.mp4              # Demonstration of core features
│   └── chat_transcript.txt         # Sample conversation examples
└── README.md                       # This file
```

##  Local Deployment and Testing

### Prerequisites

- **Ollama** installed and running locally
- **AnythingLLM** desktop application or local installation


 

1. **Load Knowledge Base in AnythingLLM**
   - Open AnythingLLM application
   - Create new workspace named "Anxiety-Support-Bot"
   - Upload all documents from `knowledge_base/` folder
   - Configure embedding settings for optimal retrieval

2. **Configure System Prompt**
   - Copy content from `prompt/system_prompt.txt`
   - Paste into AnythingLLM system prompt configuration
   - Save configuration

3. **Test Core Functionality**
   - Start conversation with test questions:
     - "I keep worrying about everything—is this anxiety?"
     - "Can you teach me a simple relaxation exercise?"
   - Verify medical disclaimers appear in responses
   - Check knowledge base citations are working

### Testing Guidelines

**Required Test Scenarios:**
-  Anxiety symptom inquiry with appropriate educational response
-  Relaxation technique request with step-by-step guidance
-  Crisis situation with immediate resource provision
-  Out-of-scope medical question with appropriate boundary setting
-  General mental health education request

**Expected Behaviors:**
- Medical disclaimer included in substantive responses
- Local Nova Scotia resources referenced appropriately
- Clear scope limitations maintained
- Evidence-based information provided with citations

##  Demo Materials

- **Video Demonstration**: `demo/demo_video.mp4` shows chatbot responding to core scenario questions
- **Chat Transcript**: `demo/chat_transcript.txt` contains sample conversations demonstrating key features

##  Usage Guidelines

### What the Chatbot CAN Do:
- Provide educational information about anxiety symptoms
- Guide users through validated self-assessment tools
- Teach evidence-based relaxation and coping techniques
- Share local mental health resources and crisis contacts
- Help users understand when to seek professional help

### What the Chatbot CANNOT Do:
- Diagnose medical or mental health conditions
- Provide treatment recommendations
- Replace professional healthcare or therapy
- Store personal health information
- Provide crisis counseling or intervention

##  Local Halifax Resources

**Emergency Services:**
- Emergency: 911
- Nova Scotia Mental Health Crisis Line: 1-888-429-8167

**Professional Services:**
- Nova Scotia Health Mental Health and Addictions Services
- Canadian Mental Health Association Nova Scotia
- Local family physicians and mental health professionals

##  Authors and Contributors

**Author**: Chidiebere Onwe 
**Date**: August 2025  


##  License and Usage

This project is developed for **educational research purposes only**. 

-
##  Final Disclaimer

**This chatbot is a student research project created for educational purposes. It does not replace professional medical advice, diagnosis, or treatment. Always consult qualified healthcare providers for mental health concerns. In crisis situations, contact emergency services immediately.**
