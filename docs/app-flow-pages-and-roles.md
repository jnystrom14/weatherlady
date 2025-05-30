# WeatherCore App Flow: Pages and User Roles

## 👤 User Roles

* **Default User**: Logged-in user (you or your wife)

  * Can view all dashboards, radar, forecasts
  * Can configure alerts and preferences
  * Can use AI Assistant
* **Guest (Optional)**: No login required

  * Limited read-only access to homepage or radar
  * No alert customization or AI assistant access (unless enabled)

## 🗺️ Core Pages

### 1. **Homepage Dashboard**

* Current weather card (temp, feels-like, wind, humidity, etc.)
* Collapsible hourly forecast section
* Collapsible 7-day forecast section
* Radar preview (click to expand)
* Toggle for light/dark mode
* Live alert banners

### 2. **Radar Page**

* Full-screen radar visualization
* Layer controls (precip, wind, temp, cloud cover)
* Time slider for looping view (past/future)
* Set center and radius of focus (default: home address)

### 3. **Forecast Explorer**

* Detailed hourly and daily forecasts
* Line/area graphs for temp, wind, humidity, precipitation
* Sunrise/sunset and moon phase indicators
* Past 7 days historical data module

### 4. **AI Assistant Page/Overlay**

* Voice or chat input field
* Natural language answers with weather data lookups
* Suggestions or example prompts
* Toggle for voice/text input

### 5. **Settings / Alerts Configuration**

* Set thresholds for custom alerts (e.g., wind > 30mph)
* Enable/disable specific alert types
* Notification preferences (browser push or in-app)

## 🔄 App Navigation Flow

* User lands on Homepage

  * Quick weather glance
  * Can tap into Forecast Explorer or full Radar
* Persistent nav bar or drawer (mobile)

  * Access AI Assistant, Settings, Logout
* Alerts and assistant can be invoked from any screen via floating icons or buttons

## 🔐 Auth Flow

* Optional login (email/password or Google)
* Once logged in, user preferences, location, and alert settings are saved
* Guest mode offers limited preview experience
