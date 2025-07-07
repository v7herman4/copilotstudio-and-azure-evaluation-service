## Table of Contents
- [Overview](../README.md#overview)
- [Requirements for Installation](requirements-for-installation.md)
- [Requirements for End Users](requirements-for-end-users.md)
- [Installation Guide](installation.md)
- [How to Use The Solution](howtousereporting.md)
- [FAQs](faq.md)
<br><br>

### How can I clean up the ConversationPromptEvaluation records as they get created?

Due to the Parent:Child relationship of the ConversationPromptEvaluation table and the parent ConversationTranscript table, the child record will get deleted as the ConversationTranscript table gets trimmed via the Bulk Delete Job. For more information, see this article:

[Download conversation transcripts in Power Apps - Microsoft Copilot Studio | Microsoft Learn](https://learn.microsoft.com/en-us/microsoft-copilot-studio/analytics-transcripts-powerapps#change-the-default-retention-period)
