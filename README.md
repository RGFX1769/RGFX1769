- 👋 Hi, I’m @RGFX1769
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
RGFX1769/RGFX1769 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
export REPLICATE_API_TOKEN=<paste-your-token-here>
curl -s -X POST \
  -H "Authorization: Token $REPLICATE_API_TOKEN" \
  -H "Content-Type: application/json" \
  -d $'{
    "version": "7de2ea26c616d5bf2245ad0d5e24f0ff9a6204578a5c876db53142edd9d2cd56",
    "input": {
      "image": "https://example.com/image.png"
    }
  }' \
  https://api.replicate.com/v1/predictions
  "completed_at": null,
  "created_at": "2023-03-08T17:54:26.385912Z",
  "error": null,
  "id": "j6t4en2gxjbnvnmxim7ylcyihu",
  "input": {"image":"https://example.com/image.png"},
  "logs": null,
  "metrics": {},
  "output": null,
  "started_at": null,
  "status": "starting",
  "model": "sczhou/codeformer",
  "version": "7de2ea26c616d5bf2245ad0d5e24f0ff9a6204578a5c876db53142edd9d2cd56"
