
Twilio Client Contact Centre Powered by Twilio-Taskrouter 

Languages: Node js
Channel: Voice
Call Type: Inbound

This implements:

-  Agent UI based on TaskRouter SDK for low latency
-  Twilio Client WebRTC agent dashboard
- Conference instruction
- Call instruction
- Conference recording
- Call holding
- Call transfers


Changes in Code needed:

---server.js file---

accountSid : Your Accounts Twilio SID
authToken : Your Accounts Auth token SID
workspaceSid : Workspace SID
workflow_sid : Workflow SID
caller_id : Inbound Contact Center phone number
wrap_up : SID of wrapup state.(If not create a new activity called wrapup)
twiml_app : SID of Twilml Voice App