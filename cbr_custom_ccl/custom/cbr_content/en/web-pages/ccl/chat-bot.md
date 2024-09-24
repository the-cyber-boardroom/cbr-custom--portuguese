## CCL Chat bot

{{render_template("llms/includes/choose-llm.html")}} 

{{chatbot   name             = "CISO " 
            initial_message  = "Hi, ask me about CCL"
            initial_prompt   = "Hello"
            edit_mode        = "false"
            platform         = "Groq (Free)"
            provider         = "Meta"
            model            = "llama3-70b-8192"

}}


<script type="module" src="/web_components/js/chat-bots/Chatbot_OpenAI.mjs"></script>
<script src="https://cdn.jsdelivr.net/npm/marked/marked.min.js"></script>
