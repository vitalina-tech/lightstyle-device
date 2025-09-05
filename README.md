# Lightstyle Device
An intelligent lighting and productivity system combining focus timers with ambient RGB lighting control

## Current Features

### Focus Timer Modes
- **Focus Session Timer**: Structured pomodoro-style work intervals
- **Flow Timer**: Flexible manual session tracking  
- Console-based interface with session summaries
- Customizable timing and break intervals

### Current Status
🚧 **Version 0.1** - Console timer foundation implemented

## Vision
A smart ambient system that combines productivity timing with intelligent lighting - creating an environment that adapts to your work rhythm and enhances focus through synchronized visual cues.

## Roadmap

### Phase 1: Software Foundation ✅
- [x] Console-based focus timer (pomodoro-style)
- [x] Console-based flow timer (flexible tracking)

### Phase 2: GUI Development  
- [ ] Tkinter interface for timer controls
- [ ] Visual countdown display
- [ ] Timer history and statistics
- [ ] Sound notifications

### Phase 3: Light Integration
- [ ] RGB color control algorithms  
- [ ] Timer-light synchronization (red=focus, green=break, blue=complete)
- [ ] Mood lighting modes independent of timers
- [ ] Circadian rhythm support (warm/cool transitions)

### Phase 4: Smart Features
- [ ] Music synchronization
- [ ] Weather-responsive colors
- [ ] Sleep/wake light simulation  
- [ ] Mobile app control
- [ ] Voice commands integration

### Phase 5: Hardware Implementation
- [ ] Raspberry Pi controller design
- [ ] RGB LED strip/smart bulb integration
- [ ] Custom 3D-printed housing
- [ ] Physical control interface
- [ ] Standalone device operation

## Current Timer Modes

**Focus Timer**: Traditional productivity technique with structured intervals
```bash
python focus_timer.py
```

**Flow Timer**: Natural work rhythm tracking with manual controls
```bash
python flow_timer.py  
```

## Future Light Modes

- 🔵 **Focus Mode**: Blue for concentration
- 🟠 **Break Mode**: Orange for rest  
- 🟢 **Complete**: Green for session completion
- 🌈 **Ambient**: Mood-responsive environmental lighting
- ☀️ **Circadian**: Natural light cycle simulation

## Tech Stack
- **Current**: Python 3.x, time module
- **Planned GUI**: Tkinter  
- **Lighting**: RGB LED control, color theory algorithms
- **Hardware**: Raspberry Pi, GPIO, PWM control
- **Future**: Mobile app integration, IoT connectivity

## Getting Started
1. Clone the repository
2. Run timer modes:
   - `python focus_timer.py` - structured productivity sessions
   - `python flow_timer.py` - flexible work tracking

## The Concept
More than just a timer or light - a complete productivity lifestyle device that understands your work patterns and creates the perfect environment for deep focus and effective breaks.
