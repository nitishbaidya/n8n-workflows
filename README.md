# n8n Workflows

A collection of n8n workflows demonstrating automation, AI integration, and data processing capabilities.

## 🚀 Workflows Overview

### 📧 Musical Newsletter Automation
**Daily personalized music curation based on weather and social sentiment**

- **Schedule**: Automated daily execution at 6 AM
- **Data Sources**: Weather API, Reddit RSS feeds
- **AI Architecture**: **Multi-agent setup** with 3 distinct AI processing steps
- **AI Integration**: Google Gemini for mood analysis
- **Output**: Email newsletter with 10+ song recommendations
- **Key Technologies**: RSS parsing, HTTP requests, AI sentiment analysis, email automation

#### Quick Start
1. Configure Google Gemini API credentials
2. Set up SMTP email settings
3. Update location coordinates for weather data (currently set to London)
4. Activate the workflow

#### Configuration Options
- **Location**: Modify latitude/longitude in weather API calls for your preferred city
- **Content Sources**: Add/remove RSS feeds from /r/feelgood, /r/upliftingnews, or other subreddits
- **Schedule**: Adjust trigger timing from default 6 AM
- **Email Recipients**: Configure distribution lists and email templates
- **Music Genres**: Customize AI prompts for specific music preferences
- **Multi-Agent Setup**: Configure different AI providers for each of the 3 processing steps:
  - **Agent 1**: Weather analysis and mood interpretation
  - **Agent 2**: Social sentiment analysis from news content
  - **Agent 3**: Music recommendation synthesis and newsletter generation
- **AI Provider Flexibility**: Mix and match providers (OpenAI, Claude, Gemini, etc.) for varying results and capabilities

#### Use Cases
- **Personal Productivity**: Daily mood-based music recommendations
- **Content Creators**: Automated playlist curation for audiences
- **Wellness Applications**: Music therapy based on environmental and social factors
- **Marketing**: Personalized customer engagement through contextual content

### 📊 Social Media Trend Analyzer
**Real-time trending topic extraction and analysis**

- **Data Source**: Trends24.in web scraping
- **Capabilities**: Browser spoofing, HTML parsing, trend extraction
- **Geography**: India-focused (expandable)
- **Key Technologies**: Web scraping, data extraction, error handling

#### Quick Start
1. Configure browser headers for web scraping
2. Set up error handling notifications
3. Test HTML parsing selectors
4. Connect Slack/Discord/Gmail for trends to be sent
5. Activate the workflow

#### Configuration Options
- **Geographic Region**: Modify URL to target different countries (currently India)
- **Scraping Frequency**: Adjust execution schedule based on needs
- **Data Output**: Configure where extracted trends are sent or stored
- **Error Handling**: Set up notifications for failed scraping attempts
- **Browser Settings**: Customize user agent and headers to avoid detection

#### Use Cases
- **Social Media Management**: Real-time trend monitoring for content planning
- **Marketing Teams**: Campaign timing based on trending topics
- **Business Intelligence**: Market sentiment and topic analysis
- **Content Strategy**: Data-driven content creation based on current trends

---

*These workflows demonstrate practical automation solutions combining multiple APIs, AI services, and data sources to create value-driven automated processes.*

**Keywords**: Multi-Agent AI Systems - AI/ML Integration - LLM Integration - AI Sentiment Analysis - AI-Powered Automation - Machine Learning Workflows - n8n Workflows - Workflow Automation - Business Process Automation - Event-driven Automation - Scheduled Workflows - Trigger-based Execution - Data Pipeline Automation - Automated Content Curation - Intelligent Data Processing - AI Content Generation - API Orchestration - Workflow Design - Process Optimization
