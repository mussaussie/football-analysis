# ⚽ Football Player Tracking & Performance Analysis

> AI-powered system for automated player detection, tracking, and performance analytics from football video footage using YOLOv8 and ByteTrack.

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![YOLOv8](https://img.shields.io/badge/YOLOv8-Ultralytics-green.svg)](https://github.com/ultralytics/ultralytics)
[![OpenCV](https://img.shields.io/badge/OpenCV-4.5+-red.svg)](https://opencv.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

*Real-time player tracking with performance metrics visualization*

---

## 🎯 Project Overview

This project automatically analyzes football match videos to extract player movement data and generate comprehensive performance statistics. Using state-of-the-art computer vision and deep learning techniques, the system tracks players throughout the match and calculates key performance indicators.

### Key Features

- 🤖 **Automated Player Detection** using YOLOv8 deep learning model
- 🔄 **Multi-Object Tracking** with ByteTrack algorithm for consistent player IDs
- 📊 **Performance Metrics**: Distance covered, speed, acceleration, activity zones
- 🔥 **Visual Analytics**: Heatmaps, trajectory plots, and statistical charts
- 📈 **Export Reports**: CSV files with detailed frame-by-frame and summary data

---

## 🚀 Quick Start

### Prerequisites
```bash
Python 3.8+
pip or conda

---

## 📊 What It Does

### Input
- Football match video (MP4, AVI, MOV formats)
- Any duration, any resolution (720p+ recommended)

### Processing Pipeline

```
Video → Frame Extraction → AI Detection → Player Tracking → 
Metric Calculation → Statistical Analysis → Visualization → Reports
```

### Output

**1. Annotated Video**
- Bounding boxes around players
- Tracking IDs displayed
- Real-time visualization

**2. Data Files**
- `player_summary.csv` - Per-player statistics
- `player_metrics.csv` - Frame-by-frame data
- `tracking_clean.csv` - Cleaned detection data

**3. Visualizations**
- Top players by distance covered
- Speed distribution histograms
- Player movement trajectories
- Activity heatmaps

![Top players by distance](images/top%20players.png)

![Speed distribution](images/speed%20distribution.png)

![Activity heatmap](images/activity%20heatmap.png)



**4. Performance Metrics**
- Total distance covered (pixels)
- Average/maximum speed
- Acceleration patterns
- Time on field
- Activity zones

---

## 🛠️ Technology Stack

| Component | Technology | Purpose |
|-----------|-----------|---------|
| **AI Detection** | YOLOv8 (Ultralytics) | Real-time object detection |
| **Tracking** | ByteTrack | Multi-object tracking with ID consistency |
| **Video Processing** | OpenCV | Frame extraction and manipulation |
| **Data Analysis** | Pandas, NumPy | Data processing and calculations |
| **Visualization** | Matplotlib, Seaborn | Chart generation and heatmaps |
| **Environment** | Jupyter Notebook | Interactive analysis |

---

### Key Insights Generated
- ⚡ Fastest player identification
- 🏃 Most active player (distance covered)
- 📍 Player positioning and movement patterns
- 🔥 Activity hotspots on field
- 📊 Team-wide performance distributions

---

## 🎓 Technical Highlights

### Computer Vision
- **YOLOv8s model** for balanced speed/accuracy
- **Confidence threshold**: 0.3 (30% minimum certainty)
- **IoU threshold**: 0.5 for duplicate removal
- **Classes detected**: Person, sports ball

### Multi-Object Tracking
- **ByteTrack algorithm** for robust tracking
- Handles occlusions and re-identification
- Maintains consistent IDs across frames
- Kalman filter for motion prediction

### Data Processing
- Frame-by-frame position tracking
- Euclidean distance calculations
- Speed and acceleration computations
- Statistical aggregation per player
- Outlier filtering for data quality

---

## 🎯 Use Cases

### Sports Teams
- Player performance monitoring
- Training load management
- Injury prevention analytics
- Tactical analysis

### Coaches & Analysts
- Match review and debriefing
- Player comparison
- Formation analysis
- Opponent scouting

### Researchers
- Sports science studies
- Algorithm benchmarking
- Dataset creation
- Performance modeling

### Students & Developers
- Computer vision portfolio project
- Machine learning practice
- Data science application
- Sports analytics learning

---

## 🚀 Future Enhancements

Potential improvements for advanced version:

- [ ] Camera calibration for real-world coordinates (meters)
- [ ] Team identification (jersey color detection)
- [ ] Ball possession tracking
- [ ] Passing network visualization
- [ ] Formation recognition
- [ ] Multi-camera fusion
- [ ] Real-time processing mode
- [ ] Web dashboard interface
- [ ] Automatic highlight generation

---

## 📚 Learning Resources

This project demonstrates:
- ✅ Computer vision and object detection
- ✅ Deep learning model deployment
- ✅ Multi-object tracking algorithms
- ✅ Data processing pipelines
- ✅ Statistical analysis
- ✅ Data visualization
- ✅ Sports analytics applications

**Concepts Covered:**
- YOLO architecture
- ByteTrack algorithm
- Kalman filtering
- Data cleaning techniques
- Feature engineering
- Aggregate statistics

---

## 🤝 Contributing

Contributions welcome! Areas for improvement:
- Additional sports support (basketball, hockey)
- Performance optimizations
- UI/UX enhancements
- Documentation improvements
- Bug fixes

---

## 📄 License

This project is licensed under the MIT License - see [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- [Ultralytics YOLOv8](https://github.com/ultralytics/ultralytics) - Object detection framework
- [ByteTrack](https://github.com/ifzhang/ByteTrack) - Multi-object tracking algorithm
- [OpenCV](https://opencv.org/) - Computer vision library
- Football analytics community for inspiration

---

## 📞 Contact

**Your Name**  
📧 Email: your.email@example.com  
🔗 LinkedIn: [linkedin.com/in/yourprofile](https://linkedin.com/in/yourprofile)  
💼 Portfolio: [yourportfolio.com](https://yourportfolio.com)

---

## ⭐ Star This Repository

If you find this project useful, please consider giving it a star! It helps others discover the project.

---

**Built with ❤️ for the sports analytics community**