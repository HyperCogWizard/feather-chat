# Featherless Chat Template

A starter template for a chat interface for the Featherless AI platform. Get started with AI-powered chat in minutes.

## 🚀 Quick Start

1. Clone the repository:
   ```bash
   git clone https://github.com/featherless/chat-template
   cd chat-template
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Copy the environment file:
   ```bash
   cp .env.example .env
   ```

4. Add your Featherless API key to `.env`

5. Start the development server:
   ```bash
   npm run dev
   ```

## 🔑 Features

- 🎨 Dark/Light theme
- 💬 Conversation management
- 🤖 Model selection
- ⚡ Streaming responses
- 📱 Mobile-responsive
- 🔒 Secure API key handling

## 🛠️ Customization

### Styling
The template uses Tailwind CSS. Customize colors and styling in `tailwind.config.js`.

### Models
Edit `POPULAR_MODELS` in `src/components/ModelSelector.jsx` to change default models.

### API
Modify API calls in `src/services/api.js` to add custom endpoints or parameters.

## 📦 Deployment

1. Build the project:
   ```bash
   npm run dev
   ```

2. Deploy to your preferred platform (Vercel, Netlify, etc.)
# Community & Support
Our growing community of developers, enthusiasts, and AI practitioners is here to help you get the most out of Featherless:
- Join our [Discord](https://discord.gg/7gybCMPjVA) community to connect with other users
- Check out our [Zero to AI blog](https://featherless.ai/blog/zero-to-ai-deploying-language-models-without-the-infrastructure-headache)
- Follow us on [X](https://x.com/FeatherlessAI) for the latest updates
- Try out [DeepSeek-R1](https://featherless.ai/blog/deepseek-r1-available-for-premium-users) with unlimited tokens on our premium plan!

## 🏗️ Architecture Documentation

Comprehensive architecture documentation with Mermaid diagrams is available:

📚 **[Architecture Documentation](./docs/architecture/README.md)** - Explore the cognitive architecture and system design

- 🏗️ [System Overview](./docs/architecture/system-overview.md) - High-level architectural patterns and cognitive flows
- 🔄 [Component Interactions](./docs/architecture/component-interactions.md) - Module relationships and bidirectional synergies  
- 📊 [Data Flow Analysis](./docs/architecture/data-flow.md) - Signal propagation pathways and state management
- 🧠 [Cognitive Patterns](./docs/architecture/cognitive-patterns.md) - Neural-symbolic integration and emergent behaviors
- ⚙️ [Implementation Pathways](./docs/architecture/implementation-pathways.md) - Recursive patterns and optimization strategies

## 📝 License

MIT