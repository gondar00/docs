# Stretch AI Product Review - Onboarding Specialist Notes

## Login & Authentication
- **Email-based authentication**: Simple, passwordless login using email + OTP
- **6-digit OTP verification**: Sent to user's email address
- **Clean UI**: Minimal, professional login interface
- **Branding**: Stretch logo prominently displayed

## Dashboard Overview (Initial Landing Page)
- **Business Performance Summary** (Last 30 days):
  - Total revenue tracking
  - Attributed revenue with percentage of total
  - Currently showing £0.00 (new account)

- **Top 5 Performance Tables**:
  - Top 5 Automations by Revenue
  - Top 5 Campaigns by Revenue
  - Both tables empty (no data yet)

- **Campaign Metrics Dashboard**:
  - Toggle between Campaigns and Automations view
  - Filter by tags functionality
  - Export functionality
  - Date range selector (default: Last 180 days)

- **Three Key Performance Areas**:
  1. **Channel Performance**: Total volume of emails, SMS, and WhatsApp sent
  2. **Engagement Performance**: Click and open rates for delivered messages
  3. **Revenue Performance**: Revenue generated from campaign clicks

- **Multi-channel Support**:
  - Email
  - SMS
  - WhatsApp

- **Visual Elements**:
  - Line charts for trend visualization
  - Tab-based navigation for different channels
  - Clean, modern dark/light theme toggle

## Sidebar Navigation
Visible menu items:
1. Overview (current page)
2. Lists
3. Templates
4. Campaigns
5. Form Builder
6. Automations
7. Media Library
8. Sales Pipeline
9. Activity Log
10. Staff Alerts
11. Integrations

## Top Navigation Bar
- WhatsApp notifications (0)
- Inbox (0)
- Location selector: "All locations"
- Theme toggle (dark/light mode)
- User profile/settings

## Initial Observations
- Clean, professional interface
- No onboarding wizard visible yet
- Need to explore Integrations section for Mindbody, WhatsApp Business, Meta Ads setup
- Dashboard is empty state - good opportunity to document the onboarding journey

---

## Next Steps
1. Explore Integrations section
2. Review onboarding flows for:
   - Mindbody connection
   - WhatsApp Business connection
   - Meta Ads connection
3. Document campaign management features
4. Review automations, forms, and other features


## Onboarding Review - Integrations

### Mindbody Integration
**Connection Process:**
- Users need to enter their Mindbody Site ID
- Help link provided to guide users to find their Site ID
- Process: Enter Site ID → Get Activation Code
- Syncs: clients, services, staff, and contracts
- Category: Ecommerce

**User Experience Notes:**
- Simple, straightforward one-field form
- Clear help documentation link
- External Mindbody support article shows Site ID location in bottom right of Mindbody interface

### WhatsApp Business Integration
**Connection Options:**
1. **Connect New Number**: Set up a new WhatsApp Business number
2. **Connect Existing WhatsApp Business App**: Link existing WhatsApp Business app number

**Connection Process:**
- Clicking either option redirects to Facebook login (OAuth flow)
- Requires Facebook account authentication
- Category: Messaging
- Purpose: Send templates and messages to customers

**User Experience Notes:**
- Modal dialog with two clear options
- Facebook OAuth integration for secure connection
- Seamless handoff to Facebook login

### Meta Ads (Facebook Ads) Integration
**Connection Process:**
- Single "Connect with Facebook" button
- OAuth flow through Facebook

**Key Features:**
- Create and manage custom audiences
- Sync customer data to Facebook
- Create and manage ad campaigns
- Track campaign performance and ROI

**Getting Started Steps:**
1. Click "Connect with Facebook" button
2. Log in to Facebook account
3. Select the ad account to connect
4. Grant necessary permissions

**Category:** Advertising

### Other Available Integrations
1. **Google Ads** - Advertising
2. **TikTok Ads** - Advertising  
3. **Shopify** - Ecommerce
4. **Google Analytics** - Analytics
5. **Zendesk** - Messaging (customer support)
6. **UPayments** - Ecommerce (payment links)
7. **Hirebob** - Ecommerce (locations and sales pipelines)

### Integration Categories
The platform organizes integrations into filterable categories:
- All Integrations
- Connected
- Messaging
- Advertising
- eCommerce
- Analytics

---

## Phase 2 Complete - Onboarding Flows Documented
Next: Review Campaign Management Features


## Campaign Management Review

### Lists Management
**List Types Available:**
1. **Dynamic Lists**: Auto-updating lists based on conditions and filters
2. **Static Lists**: Fixed lists imported from CSV
3. **Form Responses**: Lists generated from form submissions
4. **WhatsApp Tags**: Lists based on WhatsApp conversation tags

**List Creation Features:**
- Condition-based filtering with multiple operators (is, is not, more than, less than, etc.)
- Add multiple conditions for complex segmentation
- CSV import with template download
- Required columns: First Name, Last Name, Email, Phone number
- Tag management for organization
- Search functionality
- Column customization

**List Display:**
- Shows Email Subscribers count
- Shows SMS Subscribers count
- Date added and Date updated tracking
- Actions menu for each list
- Pagination (10 rows per page default)

### Templates Management
**Template Types:**
1. **Email Templates**
2. **SMS Templates**
3. **WhatsApp Templates**

**Email Template Editor Features:**
- Template Name field (required)
- Email Subject field (required)
- Drag-and-drop content builder
- Desktop/Mobile preview toggle
- Content blocks available:
  - Columns
  - Button
  - Divider
  - Heading
  - Text
  - Image
  - Video
  - Social
  - Menu
  - HTML (custom code)
- Undo/Redo functionality
- Visual preview canvas

**Template Organization:**
- All Templates tab
- Template Gallery tab
- Refresh functionality
- Empty state with clear CTA

### Campaigns Management
**Campaign Overview:**
- List view and Calendar view options
- Date range filter (default: last 30 days)
- Search campaigns functionality
- Campaigns vs A/B Tests tabs

**Campaign Analytics Dashboard:**
Five key metrics tracked:
1. **Delivered**: Total messages delivered
2. **Opened**: Open rate percentage
3. **Clicked**: Click rate percentage
4. **Bounced**: Bounce rate percentage
5. **Complaints**: Complaint rate percentage

**Campaign Creation:**
Required fields:
1. **Campaign Name**: Descriptive name for the campaign
2. **Recipients**: Select target list(s)
3. **Exclude Recipients**: Optional exclusion list
4. **Template**: Select pre-created template

**Schedule Settings:**
Two frequency options:
1. **Send one time**: Single campaign execution
   - Select specific date and time
   - Timezone displayed (Europe/London)

2. **Recurring schedule**: Automated recurring campaigns
   - Recurring Schedule dropdown with interval options
   - Start date and time selection
   - Interval frequency input

**Campaign Features:**
- Date range filtering
- List and Calendar view modes
- A/B Testing capability (separate tab)
- Real-time analytics tracking
- Empty state guidance

---

## Phase 3 Complete - Campaign Management Documented
Next: Review Automations, Integrations, and Form Management


## Automations Review

**Dashboard Overview:**
- **Library:** Active Automations (main view)
- **Discover Automations:** Pre-built templates for quick setup, categorized by channel:
  - Email Automations
  - SMS Automations
  - WhatsApp Automations
- **Filtering:** Filter by Category, Status (Active Only, Disabled Only)
- **Actions:** Manage Categories, Reset All Filters, Export Data, Settings

**Pre-built Automation Categories (Email Example):**
- Converting leads (Welcome new clients)
- Client engagement (Strengthen loyalty)
- Class pack management (Remind about expiring packages)
- Appointments (Send reminders, feedback requests)
- Personal training (Automate personalized messages)
- Meta lead conversion (Connect with leads from Facebook ads)
- Google lead conversion (Engage and convert leads from Google Ads forms)
- Form submissions (Send instant responses)

**User Experience Notes:**
- Clear categorization of automation templates by channel and purpose.
- Focus on key business outcomes (lead conversion, engagement, retention).

## Form Management Review

**Forms Management Overview:**
- Empty state with clear CTA: "Create First Form"
- **Actions:** Refresh, Add Form, Search forms

**Form Creation Process:**
- **Step 1: Create New Form**
  - Requires a **Form Name** (e.g., Contact Form, Registration Form)
  - Next button leads to the form editor (not explored, but implied)

**User Experience Notes:**
- Simple, two-step process to start a new form.
- Forms are used for data collection, which can feed into Dynamic Lists and Automations.

---

## Phase 4 Complete - Automations, Integrations, and Form Management Documented
Next: Review Dashboard, Conversations, and Contacts


## Dashboard Overview (Detailed)

The Dashboard provides a comprehensive view of marketing performance, focusing on campaign and automation metrics.

### Key Metrics

| Metric | Description |
| :--- | :--- |
| **Total Revenue** | Total revenue generated in the last 30 days. |
| **Attributed Revenue** | Revenue directly attributed to marketing efforts (campaigns/automations). |
| **Top 5 Automations/Campaigns** | Tables showing the top performing automations and campaigns by revenue. |

### Campaign Metrics Dashboard

This section visualizes performance data across all campaigns, with channel-specific breakdowns for Email, SMS, and WhatsApp.

| Performance Area | Metrics Tracked |
| :--- | :--- |
| **Channel Performance** | Total Volume of Emails, SMS, and WhatsApp Sent. |
| **Engagement Performance** | Percentage of delivered messages that are clicked and opened (Open Rate, Click Rate). |
| **Revenue Performance** | Revenue generated from users who clicked on campaigns, broken down by channel. |

**Filtering and Export:**
- Date range selector (default: Last 180 days)
- Export button for data download
- Filter by tags
- Toggle between Campaigns and Automations view

---

## Conversations (WhatsApp) Review

**Navigation:**
- Accessed via the WhatsApp icon in the top bar or the sidebar.

**Features:**
- **Inbox:** All Messages, Unread tabs.
- **Search:** Search conversations by name, email, or mobile number.
- **Empty State:** "No WhatsApp conversations" message.

**User Experience Notes:**
- Centralized inbox for managing multi-channel conversations.
- Requires WhatsApp Business integration to be active.

---

## Contacts (Lists) Review

**Navigation:**
- Accessed via the "Lists" link in the sidebar.

**Features:**
- **Member Lists:** Manage member lists for targeted campaigns.
- **List Types:** Dynamic, Static, Form Responses, WhatsApp Tags.
- **Segmentation:** Dynamic lists allow complex condition-based filtering.
- **Import:** Static lists support CSV import.
- **Metrics:** Tracks Email Subscribers and SMS Subscribers counts.

---

## Phase 5 Complete - Dashboard, Conversations, and Contacts Documented
Next: Create comprehensive documentation pages
