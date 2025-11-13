# OpenCharacters - Character.AI Alternative

A modern, feature-rich alternative to Character.AI with support for multiple AI services and enhanced customization options.

![OpenCharacters](https://img.shields.io/badge/Version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Status](https://img.shields.io/badge/Status-Production%20Ready-brightgreen.svg)

## ✨ Features

### 🎭 **Character Management System**
- **Advanced Character Creation**: Create detailed AI characters with custom personalities, backstories, and behavioral patterns
- **Character Templates**: Pre-built characters including Game Master, Therapist, and Creative Writing Partner
- **Character Sharing**: Generate shareable links to share your characters with others
- **Character Import/Export**: Export character data in JSON format for backup and sharing

### 🤖 **AI Content System**
- **Multi-Service Support**: 
  - **Groq** (Kimi model) - Fast inference with high-quality responses
  - **OpenAI** (GPT-4, GPT-3.5-turbo) - Industry-leading language models
  - **Anthropic** (Claude) - Safe and helpful AI assistance
  - **Hugging Face** - Open-source model integration
- **Real-time Streaming**: Experience fluid conversations with streaming responses
- **Conversation History**: Persistent chat history with export functionality
- **Smart Context Management**: AI maintains conversation context across messages

### 🎨 **Advanced Customization**
- **Prompt Engineering**: Advanced prompt system for fine-tuning character behavior
- **Response Controls**: Adjustable creativity (temperature), response length, and system prompts
- **Two-Instruction System**: Separate AI content system and character prompt system
- **Temperature Control**: Fine-tune response randomness from 0.0 to 2.0
- **Token Management**: Control response length with custom token limits

### 📊 **Advanced Analytics Dashboard**
- **Real-time Statistics**: Track conversations, messages, and character usage
- **Performance Metrics**: Monitor API response times and success rates
- **Usage Analytics**: Detailed breakdown of AI service usage
- **Visual Charts**: Interactive charts and graphs for data visualization
- **Character Insights**: Most used characters and engagement scores
- **Session Tracking**: Monitor conversation session lengths and patterns

### 🔌 **Plugin System for Extensions**
- **Plugin Management**: Install, enable, and manage third-party plugins
- **Built-in Plugins**: Character templates, export manager, analytics plus
- **Plugin Marketplace**: Browse and install community-created plugins
- **Plugin Development API**: Create custom plugins with JavaScript API
- **Plugin Categories**: Organized by utility, analytics, character, etc.
- **Version Management**: Track plugin versions and updates

### 👥 **Team Collaboration Features**
- **Team Management**: Invite team members and manage permissions
- **Shared Character Library**: Collaborate on character creation
- **Real-time Collaboration**: Edit characters with team members
- **Permission Controls**: Admin, edit, and read-only permissions
- **Team Settings**: Configure collaboration preferences
- **Member Status**: Online/offline status tracking

### 📈 **API Rate Limiting & Usage Tracking**
- **Real-time Monitoring**: Track API usage across all services
- **Rate Limit Alerts**: Automatic warnings at 75% and 90% usage
- **Cost Tracking**: Monitor spending across different AI services
- **Usage Analytics**: Daily, weekly, and monthly usage reports
- **Service Distribution**: See which services you use most
- **Usage History**: Historical data for usage pattern analysis

### 💾 **Privacy & Security**
- **Local Storage**: All character data and conversations stored locally in your browser
- **No Server Required**: Runs entirely in the browser - no data sent to external servers
- **API Key Protection**: Secure API key storage with local caching
- **Offline Capable**: Works offline after initial load

### 📱 **Modern Interface**
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Glass Morphism UI**: Modern frosted glass design with smooth animations
- **Dark/Light Themes**: Adaptive interface with beautiful gradients
- **Accessibility**: Keyboard navigation and screen reader support
- **Real-time Updates**: Live typing indicators and message animations

## 🚀 Quick Start

### 1. **Get API Keys**
Choose your preferred AI service and obtain an API key:
- **Groq**: [Get free API key](https://console.groq.com/) - Recommended for speed
- **OpenAI**: [Get API key](https://platform.openai.com/api-keys)
- **Anthropic**: [Get API key](https://console.anthropic.com/)
- **Hugging Face**: [Get API key](https://huggingface.co/settings/tokens)

### 2. **Access OpenCharacters**
Simply open `index.html` in your web browser. No installation required!

### 3. **Configure Your Service**
1. Select your preferred AI service from the dropdown
2. Enter your API key in the sidebar
3. Click "Test Connection" to verify connectivity

### 4. **Create or Select a Character**
- Choose from pre-built characters in the sidebar
- Create your own character by clicking "New Character"
- Right-click existing characters to edit them

### 5. **Start Chatting**
- Select a character to begin the conversation
- Type your message and press Enter or click Send
- Enjoy natural, streaming conversations!

## 🛠️ Installation

### Option 1: Direct Usage (Recommended)
1. Download the `index.html` file
2. Open it in any modern web browser
3. Configure your API keys and start chatting!

### Option 2: Local Development
```bash
# Clone the repository
git clone https://github.com/terastudio-org/OpenCharacters.git
cd OpenCharacters

# Serve locally (optional, for development)
python -m http.server 8000
# or
npx serve .
```

### Option 3: Host on GitHub Pages
1. Fork this repository
2. Enable GitHub Pages in repository settings
3. Access your hosted version at `https://yourusername.github.io/OpenCharacters`

## 📚 Usage Guide

### **Quick Start Guide**
1. **Choose AI Service**: Select from Groq, OpenAI, Anthropic, or Hugging Face
2. **Get API Key**: Obtain and enter your preferred service API key
3. **Test Connection**: Verify connectivity with the test button
4. **Select/Create Character**: Choose from pre-built characters or create your own
5. **Start Chatting**: Begin conversations with real-time streaming responses

### **Character Creation Process**

1. **Basic Information**
   - **Name**: Your character's name
   - **Description**: Brief character overview
   - **Avatar**: Optional image URL

2. **Character Prompt** (Core System)
   - Define personality traits
   - Specify speaking style
   - Set behavioral patterns
   - Establish background and context

3. **Advanced Settings**
   - **Creativity (Temperature)**: 0.0 (Focused) to 2.0 (Creative)
   - **Response Length**: Control token usage
   - **System Prompt**: Advanced AI instructions

### **Advanced Features Usage**

#### **Analytics Dashboard**
- Click "Analytics" in the sidebar to view comprehensive usage statistics
- Monitor conversation counts, message volumes, and character engagement
- Track API usage patterns and performance metrics
- View most-used characters and session analytics

#### **Plugin System**
- Access "Plugins" from the sidebar to manage extensions
- Install plugins from the marketplace for enhanced functionality
- Built-in plugins include character templates and export manager
- Create custom plugins using the provided development API

#### **Team Collaboration**
- Use "Team" feature to collaborate on character creation
- Invite team members and share character libraries
- Manage permissions for different access levels
- Real-time collaboration on character development

#### **API Rate Limiting & Usage Tracking**
- Monitor real-time API usage across all services
- Receive automatic alerts at 75% and 90% usage thresholds
- Track costs and usage patterns for budget management
- View detailed usage analytics and historical data

### **Character Prompt Best Practices**

**Example Character Prompt:**
```
You are Dr. Sarah Chen, a compassionate therapist with 15 years of experience. 
You speak in a warm, understanding tone and always validate the person's feelings. 
You ask thoughtful follow-up questions that help people explore their emotions deeply. 
You maintain professional boundaries while being genuinely caring. 
Always avoid giving medical advice - focus on emotional support and coping strategies.
```

### Two-Instruction System

This application implements a sophisticated two-instruction system:

1. **AI Content System**: Manages real-time conversations, streaming responses, context preservation, and multi-service integration
2. **Character Prompt System**: Handles character creation, personality definition, behavior control, and response customization

This separation ensures optimal performance and user experience.

## 🔧 Configuration

### Service-Specific Settings

#### Groq Configuration
- **API Base**: `https://api.groq.com/openai/v1`
- **Recommended Models**: 
  - `moonshotai/kimi-k2-instruct-0905` (Kimi - Best balance)
  - `meta-llama/llama-3.1-70b-versatile` (Llama 70B - Most capable)
  - `mixtral-8x7b-32768` (Mixtral - Fast responses)

#### OpenAI Configuration
- **API Base**: `https://api.openai.com/v1`
- **Recommended Models**:
  - `gpt-4` (Best quality, higher cost)
  - `gpt-4-turbo` (Fast and capable)
  - `gpt-3.5-turbo` (Cost-effective)

#### Anthropic Configuration
- **API Base**: `https://api.anthropic.com/v1`
- **Recommended Models**:
  - `claude-3-opus-20240229` (Most capable)
  - `claude-3-sonnet-20240229` (Balanced)
  - `claude-3-haiku-20240307` (Fastest)

### Browser Compatibility
- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+

## 🎯 Use Cases

### **Personal Use**
- Creative writing assistance and storytelling
- Role-playing games and character development
- Emotional support and therapeutic conversations
- Learning and educational discussions

### **Professional Use**
- Content creation and copywriting
- Customer service simulation
- Training and education scenarios
- Research and analysis

### **Entertainment**
- Interactive storytelling
- Character development for games
- Creative collaboration
- Fun and engaging conversations

## 🔒 Privacy & Security

### **Data Handling**
- All character data and conversations are stored locally
- No data is transmitted to external servers except API calls
- API keys are stored securely in browser localStorage
- No user analytics or tracking

### **Best Practices**
- Regularly rotate your API keys
- Use environment-specific API keys when possible
- Review AI service privacy policies
- Consider using VPN for additional privacy

## 🚀 Advanced Features

### **Character Sharing**
Generate shareable links for your characters:
```
https://yoursite.com/OpenCharacters?char=%7B%22name%22%3A%22Dr.%20Sarah%22...
```

### **Export Functionality**
Export chat histories and character data in JSON format for backup or sharing.

### **Keyboard Shortcuts**
- `Enter`: Send message
- `Shift + Enter`: New line
- `Ctrl/Cmd + N`: New character

### **Custom Styling**
The application uses CSS custom properties for easy theming. Modify the CSS variables in the `<style>` section to customize colors and appearance.

## 🤝 Contributing

We welcome contributions! Please read our contributing guidelines before submitting pull requests.

### **Development Setup**
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

### **Areas for Contribution**
- New AI service integrations
- Additional character templates
- UI/UX improvements
- Performance optimizations
- Mobile experience enhancements
- Accessibility improvements

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **OpenCharacters Original**: Based on the work of [josephrocca](https://github.com/josephrocca/OpenCharacters)
- **AI Services**: Thanks to Groq, OpenAI, Anthropic, and Hugging Face for their APIs
- **Design Inspiration**: Modern chat interfaces and character.AI platforms
- **Community**: The open-source AI and development communities

## 🐛 Issues & Support

### **Common Issues**
1. **API Connection Fails**: Verify your API key and service configuration
2. **Characters Not Saving**: Check browser localStorage permissions
3. **Mobile Performance**: Some features may be limited on older devices

### **Getting Help**
- Check the [Issues](https://github.com/terastudio-org/OpenCharacters/issues) page
- Review the documentation above
- Contact the maintainers

## 📈 Roadmap

### **Planned Features**
- [ ] Multi-language support
- [ ] Advanced video chat integration
- [ ] Advanced character marketplace

### **Version History**
- **v1.0.0**: Initial release with multi-service support
- **v1.1.0**: Enhanced with analytics, plugins, team collaboration, and usage tracking
- **v1.2.0**: [Planned] Multi-language support and video chat integration

---

## 💡 Tips for Best Experience

1. **Start with Groq**: Fastest API with generous free tier
2. **Use Character Templates**: Get inspired by pre-built characters
3. **Experiment with Temperature**: Adjust for desired creativity level
4. **Save Regularly**: Export important characters and conversations
5. **Right-click Characters**: Quick access to edit functionality

---

**Built with ❤️ by the OpenCharacters team**

*OpenCharacters - Making AI character interactions accessible to everyone.*
