<div align="center">
  <img src="https://creeble.io/images/og-image.png" alt="Creeble - Transform Notion to REST API"/>
</div>

# 👋 Welcome to Creeble

## 🚀 What is Creeble?

**Creeble** transforms your Notion databases into production-ready REST/GraphQL APIs with real-time sync, advanced caching, and enterprise-grade security. No coding required!

### ✨ Key Features

- 🔄 **Real-time Sync** - Automatic synchronization with your Notion workspace
- ⚡ **Lightning Fast** - Global CDN with intelligent caching
- 🔒 **Enterprise Security** - API key authentication, rate limiting, and encryption
- 📊 **Analytics Dashboard** - Track usage, performance, and costs
- 🌍 **Global Infrastructure** - Powered by Cloudflare's edge network
- 🛠️ **Developer Friendly** - RESTful API with comprehensive documentation

## 🚀 Getting Started

### For Users
1. Sign up at [creeble.io](https://creeble.io)
2. Connect your Notion workspace
3. Select databases to sync
4. Get your API key
5. Start making requests!

## 📚 API Documentation

### Base URL
```
https://creeble.io/api/v1/{your-endpoint}
```

### Authentication
```bash
curl -H "X-API-Key: your-api-key" \
  https://creeble.io/api/v1/your-endpoint
```

### Example Response
```json
{
  "data": [
    {
      "id": "123",
      "properties": {
        "title": "Example Item",
        "status": "Active"
      }
    }
  ],
  "meta": {
    "total": 42,
    "per_page": 10
  }
}
```

## 🔗 Links

- 🌐 [Website](https://creeble.io)
- 📚 [Documentation](https://creeble.io/documentation)
- 💬 [Support](https://creeble.io/contact)

---

<div align="center">
  <p>Built with ❤️ by the Creeble Team</p>
  <p>Transform your Notion databases into powerful APIs today!</p>
</div>
