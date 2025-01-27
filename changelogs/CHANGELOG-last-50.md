Changelog from 2024-12-16T22:52:23+00:00 to 2024-12-18T18:48:28+00:00:
1. **Introduction of Admin API Keys:**
   - New endpoints for managing admin API keys have been added, allowing administrators to list, create, retrieve, and delete keys. This enhances security and control over API access within your organization.

2. **Changes to Organization Invites:**
   - Invite-related operations now support specifying projects, enabling you to control project access for invitees. This simplifies managing project-specific permissions within your organization.

3. **Enhancements in Example Payloads and Requests:**
   - Example requests and responses have been updated to showcase new features like including `projects` in invites. These examples guide you in implementing the latest API capabilities accurately.

4. **Documentation and Meta Information Updates:**
   - The API documentation has been reorganized for better clarity, making it easier for you to find and understand relevant information. This ensures efficient use of the API and adherence to best practices.

5. **Deprecation and Renaming of Legacy Features:**
   - Some older features have been renamed or reclassified, reflecting a transition towards newer technologies. Update your applications to align with the current focus of the API offerings.

6. **Semantic and Descriptive Changes:**
   - Updates to descriptions and semantics provide clearer explanations, reducing potential confusion. This ensures you correctly implement the API functionalities.

This changelog is designed to be developer-friendly, focusing on the practical implications of each change and how they enhance your ability to use the API effectively.

Changelog from 2024-12-18T18:48:28+00:00 to 2024-12-18T23:08:33+00:00:
1. **New Schema Components Added**  
   We’ve added several new schemas like `RealtimeResponseCreateParams` and `FineTuneSupervisedMethod`. These give you more options for configuring real-time sessions and fine-tuning methods, making your applications more dynamic.

2. **Improved Schema Descriptions**  
   Descriptions for message types such as `ChatCompletionRequestAssistantMessage` have been clarified. This helps you understand how to correctly format and send messages to the API.

3. **Enhanced Fine-Tuning Configuration**  
   The new `method` property replaces the deprecated `hyperparameters` for fine-tuning jobs. This makes configuring fine-tuning more intuitive and organized.

4. **Real-Time Session Support Added**  
   The new `/realtime/sessions` endpoint allows you to create and manage real-time sessions. This supports both audio and text, enabling more interactive model communication.

5. **Updated Tool Interaction Configuration**  
   We replaced the `function_call` parameter with `tool_choice`, offering you detailed control over tool usage during model responses. This flexibility helps optimize how the model performs tasks.

6. **Expanded Voice and Audio Options**  
   We’ve updated the list and description of available model voices. Choose the best voice for your audio interactions, but remember, it can’t be changed once audio is used in a session.

7. **Deprecated Schemas Removed**  
   We’ve removed outdated schemas like `FinetuneCompletionRequestInput`. Make sure to transition to the new schemas to stay current with the API standards. 

This changelog is designed to be concise and straightforward, ensuring you can quickly grasp the updates and how they impact your development work.