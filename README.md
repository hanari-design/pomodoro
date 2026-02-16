# 🍅 Pomodoro Timer

A beautiful, modern Pomodoro Timer web application with customizable durations, session tracking, and browser notifications.

![Pomodoro Timer](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

## ✨ Features

- **Three Timer Modes**
  - Work sessions (default: 25 minutes)
  - Short breaks (default: 5 minutes)
  - Long breaks (default: 15 minutes)

- **Full Timer Controls**
  - Play/Pause functionality
  - Reset timer to current mode's duration
  - Skip to next session

- **Session Tracking**
  - Automatic session counter for completed work sessions
  - Visual progress ring that animates during countdown

- **Customization**
  - Adjust duration for each mode (1-60 minutes)
  - Apply settings button to update timer with custom durations

- **Visual Feedback**
  - Beautiful gradient backgrounds that change with each mode
  - Smooth animations and transitions
  - Modern glassmorphic design

- **Notifications**
  - Browser notifications when sessions complete
  - Auto-switch to appropriate break after work sessions

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No installation or build process required!

### Installation

1. Download the `pomodoro-timer.html` file
2. Open it in your web browser
3. That's it! The timer is ready to use

Alternatively, you can host it on any web server or use it locally.

## 📖 How to Use

### Basic Usage

1. **Choose a Mode**: Click on "Work", "Short Break", or "Long Break" buttons
2. **Start Timer**: Click the play button (▶) in the center
3. **Pause**: Click the pause button (⏸) to pause the timer
4. **Reset**: Click the reset button (↻) to reset to the current mode's duration
5. **Skip**: Click the skip button (⏭) to move to the next session

### Customizing Durations

1. Enter your desired minutes in the input fields:
   - **Work**: Duration for work sessions (1-60 minutes)
   - **Short**: Duration for short breaks (1-30 minutes)
   - **Long**: Duration for long breaks (1-60 minutes)

2. Click the **"Apply Settings"** button to update the timer

3. The timer will reset to the new duration for the current mode

### Notifications

- On first use, allow browser notifications when prompted
- You'll receive a notification when each session completes
- Notifications work even when the tab is in the background

## 🎨 Color Schemes

The timer features dynamic gradient backgrounds:

- **Work Mode**: Purple gradient (Indigo to Violet)
- **Short Break**: Teal gradient (Green to Blue)
- **Long Break**: Pink gradient (Magenta to Rose)

## 🎯 Pomodoro Technique

This timer follows the classic Pomodoro Technique:

1. Work for 25 minutes (1 Pomodoro)
2. Take a 5-minute short break
3. After 4 Pomodoros, take a 15-minute long break
4. Repeat the cycle

The timer automatically suggests the appropriate break after work sessions:
- After sessions 1-3: Short break
- After session 4: Long break (cycle resets)

## 🛠️ Technical Details

### Built With

- **HTML5**: Structure and markup
- **CSS3**: Styling with modern features (gradients, animations, flexbox)
- **JavaScript**: Timer logic and interactivity
- **Bootstrap 5.3.8**: Responsive grid system
- **Google Fonts**: Poppins font family

### Browser Compatibility

- ✅ Chrome/Edge (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

### Features Used

- CSS Gradients & Animations
- SVG for circular progress indicator
- Web Notifications API
- LocalStorage-ready (can be extended)

## 📱 Responsive Design

The timer is fully responsive and works great on:
- Desktop computers
- Tablets
- Mobile phones

The layout automatically adjusts for smaller screens.

## 🔧 Customization

### Changing Colors

To customize the color scheme, modify the gradient values in the CSS:

```css
body.work-mode {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}
```

### Modifying Default Durations

Change the default values in the HTML input fields:

```html
<input type="number" id="workInput" class="form-control" value="25" min="1" max="60" />
```

### Adding Sound Notifications

You can extend the timer to play sounds by adding audio elements and playing them when sessions complete.

## 📝 License

This project is open source and available under the MIT License.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page or submit a pull request.

## 💡 Tips for Productivity

- **Eliminate distractions** during work sessions
- **Don't skip breaks** - they're essential for maintaining focus
- **Track your sessions** to understand your productivity patterns
- **Adjust durations** to find what works best for you
- **Use the notifications** to stay on track even when multitasking

## 🙏 Acknowledgments

- Inspired by the Pomodoro Technique created by Francesco Cirillo
- Built with modern web technologies and best practices
- Designed for simplicity and effectiveness

---

**Happy Productivity! 🍅⏱️**

*"Work smarter, not harder"*
