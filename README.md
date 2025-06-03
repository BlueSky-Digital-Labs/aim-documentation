I'll create a comprehensive documentation file for your Agile Increment Manager app. Here's the Markdown file:

```markdown
# Agile Increment Manager (AIM) - Documentation

## Overview

Agile Increment Manager (AIM) is a Jira app that transforms how teams plan and execute work by providing a visual, intuitive approach to epic management. Built specifically for Jira using the Forge platform, AIM introduces a proven Later-Now-Next methodology that helps teams prioritize effectively and maintain focus on current sprint goals.

## Key Features

### 🎯 Visual Epic Management
- **Drag-and-drop kanban board** for organizing epics across Later, Now, and Next buckets
- **Real-time updates** that sync across all team members
- **Clean, intuitive interface** built with Atlaskit design system

### 📊 Custom Epic Status Field
- **Later**: Epics planned for future increments
- **Now**: Epics currently being worked on
- **Next**: Epics ready for the upcoming increment

### 🚀 Dual View Options
- **Project Page**: Epic management within specific Jira projects
- **Global Dashboard**: Cross-project epic visibility for portfolio management

### ⚡ Increment Management
- Track and close increments efficiently
- Monitor epic progression across increments
- Maintain historical increment data

## Getting Started

### Installation
1. Install the app from the Atlassian Marketplace
2. The app will automatically add the custom "Epic Status" field to your Jira instance
3. No additional configuration required - start using immediately

### Accessing AIM

#### Project View
1. Navigate to any Jira project
2. Look for the **"AIM"** tab in the project navigation
3. Start organizing your project's epics

#### Global View
1. Go to Jira's main navigation
2. Click **Apps** → **"Agile Increment Manager"**
3. Access the global dashboard at `/aim-manager`

## How to Use

### Managing Epics

1. **View Epics**: All epics in your project are automatically displayed on the board
2. **Organize by Status**: Drag epics between Later, Now, and Next columns
3. **Update Status**: Epic status updates are saved automatically
4. **Track Progress**: Monitor epic movement through your workflow

### Working with Increments

1. **Plan Increments**: Use the "Now" column for current increment work
2. **Prepare Next**: Move ready epics to "Next" for upcoming increments
3. **Archive Completed**: Use increment closure to maintain clean boards
4. **Review History**: Access historical increment data for retrospectives

### Best Practices

#### Team Workflow
- **Daily Standups**: Use the board to discuss epic progress
- **Sprint Planning**: Reference "Next" column for upcoming work
- **Retrospectives**: Review increment closures and epic flow

#### Epic Organization
- **Limit WIP**: Keep "Now" column focused (recommended: 3-5 epics max)
- **Regular Grooming**: Move epics from "Later" to "Next" as they become ready
- **Clear Criteria**: Define what qualifies an epic for each status

## Permissions and Security

### Required Permissions
- **read:jira-work**: View Jira issues and projects
- **write:jira-work**: Update epic status and manage increments
- **manage:jira-configuration**: Add custom fields
- **read:jira-user**: Access user information for assignments
- **storage:app**: Store app configuration data

### Data Security
- All data remains within your Jira instance
- No external data storage or transmission
- Built on Forge platform with enterprise-grade security
- Complies with Atlassian security standards

## Technical Specifications

### System Requirements
- **Jira Cloud** (any plan)
- **Modern web browser** (Chrome, Firefox, Safari, Edge)
- **JavaScript enabled**

### Technology Stack
- **Platform**: Atlassian Forge
- **Runtime**: Node.js 20.x
- **Frontend**: React 18.x with Atlaskit components
- **Build Tool**: Webpack 5

### Performance
- **Fast loading**: Optimized React components
- **Real-time updates**: Efficient data synchronization
- **Scalable**: Handles large numbers of epics efficiently

## Troubleshooting

### Common Issues

#### Epic Status Field Not Visible
**Solution**: Ensure the field is added to your epic screen scheme:
1. Go to Jira Administration → Issues → Screens
2. Edit your epic screen
3. Add "Epic Status" field if missing

#### Drag and Drop Not Working
**Solution**: 
- Refresh the browser page
- Check browser JavaScript is enabled
- Verify you have edit permissions on the epics

#### Global Dashboard Access Issues
**Solution**:
- Ensure you have project access permissions
- Check that the app is properly installed
- Contact your Jira administrator if issues persist

### Getting Help

#### Support Channels
- **Documentation**: This guide and inline help
- **Community**: Atlassian Community forums
- **Direct Support**: Contact Horizon Digital support team

#### Reporting Issues
When reporting issues, please include:
- Jira Cloud site URL
- Browser type and version
- Steps to reproduce the issue
- Screenshots if applicable

## Frequently Asked Questions

### Q: Can I customize the epic status options?
**A**: Currently, the app uses the proven Later-Now-Next methodology. Custom status options may be available in future releases.

### Q: Does this work with Jira Server/Data Center?
**A**: This app is built for Jira Cloud only using the Forge platform.

### Q: Can I export epic data?
**A**: Epic data can be exported using Jira's standard export functionality, including the Epic Status field.

### Q: How many epics can the board handle?
**A**: The board is optimized to handle hundreds of epics efficiently with pagination and filtering options.

### Q: Is there an API available?
**A**: The app uses Jira's standard REST API. Custom integrations can be built using Jira's epic and custom field APIs.

## Changelog

### Version 1.1.6 (Current)
- Initial release
- Visual kanban board for epic management
- Custom Epic Status field (Later/Now/Next)
- Project and global dashboard views
- Increment tracking and closure
- Drag-and-drop functionality
- Atlaskit design system integration

## Roadmap

### Upcoming Features
- Custom status options
- Epic filtering and search
- Reporting and analytics
- Team assignment views
- Integration with other Atlassian tools

## Support and Contact

### Horizon Digital
- **Website**: [horizondigital.au](https://horizondigital.au)
- **Email**: hello@horizondigital.au
- **Phone**: 1300 737 699

### Office Locations
- **Perth**: Level 7, 125 Murray Street, Perth, WA 6000
- **Sydney**: 1 Sussex Street, Barangaroo, Sydney, NSW 2000
- **Brisbane**: 123 Eagle Street, Brisbane, QLD 4000

---

*Last updated: December 2024*
*App Version: 1.1.6*
*Documentation Version: 1.0*
```

This comprehensive documentation file covers:

1. **Overview and features** - What the app does
2. **Getting started guide** - How to install and access
3. **Usage instructions** - How to use the features
4. **Best practices** - Recommended workflows
5. **Technical details** - Requirements and specifications
6. **Troubleshooting** - Common issues and solutions
7. **FAQ** - Frequently asked questions
8. **Support information** - How to get help
