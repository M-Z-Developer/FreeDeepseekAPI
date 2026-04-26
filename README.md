## 🔧 Features

- ✅ **No API key required** - Completely free access
- ✅ **Unlimited requests** - No usage limits or quotas
- ✅ **Always available** - 24/7 uptime

## 📋 Usage Guidelines

1. Use the API responsibly and ethically
2. Respect rate limits (if implemented for stability)
3. Report any issues via GitHub Issues

## ⚠️ Important Notes

- The endpoint URL may change periodically
- Not affiliated with DeepSeek

---

**Access the API**: https://dev-mapideepz.pantheonsite.io/Deep/index.php

POST /Deep/index.php HTTP/1.1
User-Agent: Mozilla/5.0 (Linux; Android 10; K) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/138.0.0.0 Mobile Safari/537.36
Host: dev-mapideepz.pantheonsite.io
Content-Type: application/json
Content-Length: 45

{
    "User": "مرحبا",
    "Think": "false"
}

او للتفكير العميق Deep
{
    "User": "مرحبا",
    "Think": "true"
}


Response : 

{
    "success": true,
    "data": {
        "response": "مرحباً! 🌟\n\nأهلاً وسهلاً بك، كيف يمكنني مساعدتك اليوم؟",
        "conversation_id": "conv_69cfbbec3f173",
        "formatted_html": "<p>مرحباً! 🌟<\/p>\n<p>أهلاً وسهلاً بك، كيف يمكنني مساعدتك اليوم؟<\/p>\n",
        "usage": {
            "prompt_tokens": 22,
            "completion_tokens": 219,
            "total_tokens": 241
        }
    },
    "request_info": {
        "user_message": "مرحبا",
        "think_mode": false,
        "model_used": "deepseek-reasoner",
        "received_at": "2026-04-03 13:09:03",
        "http_code": 200
    }
}


Response Deep Thinking : 

{
    "success": true,
    "data": {
        "response": "مرحباً! أهلاً وسهلاً بك. كيف يمكنني مساعدتك اليوم؟ 😊",
        "conversation_id": "conv_69cfbcaa8e381",
        "formatted_html": "<p>مرحباً! أهلاً وسهلاً بك. كيف يمكنني مساعدتك اليوم؟ 😊<\/p>\n",
        "usage": {
            "prompt_tokens": 22,
            "completion_tokens": 174,
            "total_tokens": 196
        }
    },
    "request_info": {
        "user_message": "مرحبا",
        "think_mode": true,
        "model_used": "deepseek-chat",
        "received_at": "2026-04-03 13:12:12",
        "http_code": 200
    }
}


*Note: The short-link step takes only seconds and ensures the service remains free and available for all serious developers.*
