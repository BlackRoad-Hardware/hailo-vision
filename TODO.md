# Hailo Vision — TODO

## [RC] Core Pipeline
- [ ] [RC] Build GStreamer pipeline for Hailo-8 inference
- [ ] [RC] Implement camera manager (RTSP, USB, CSI)
- [ ] [RC] Multi-camera multiplexing with frame scheduling
- [ ] [RC] Model manager with local caching and hot-swap
- [ ] [RC] Pre/post-processing pipeline (resize, NMS, filtering)
- [ ] [RC] Detection event dispatcher (webhook, MQTT, RoadFlow)

## [RC] Models
- [ ] [RC] Pre-compile YOLOv8n/s/m for Hailo-8
- [ ] [RC] Pre-compile SSD MobileNet v2
- [ ] [RC] Pre-compile RetinaFace for face detection
- [ ] [RC] Pre-compile ArcFace for face recognition
- [ ] [RC] Pre-compile DeepSORT for object tracking
- [ ] [RC] Pre-compile PoseNet for pose estimation
- [ ] [RC] Custom model compilation pipeline (ONNX to HEF)

## [RC] Detection Zones
- [ ] [RC] Polygon zone definition interface
- [ ] [RC] Zone intrusion detection logic
- [ ] [RC] Dwell time tracking per zone
- [ ] [RC] Multi-zone event correlation
- [ ] [RC] Time-based alert rules (after hours, schedules)

## [RC] Analytics
- [ ] [RC] People counting with entry/exit tracking
- [ ] [RC] Heatmap generation from detection data
- [ ] [RC] Path tracking and trajectory analysis
- [ ] [RC] Traffic flow visualization
- [ ] [RC] Grafana dashboard templates

## [RC] Storage & Logging
- [ ] [RC] SQLite event log with FTS5 search
- [ ] [RC] Optional clip recording on detection events
- [ ] [RC] PostgreSQL backend for fleet-scale deployments
- [ ] [RC] Event data export (CSV, JSON)
- [ ] [RC] Audit log for compliance

## [RC] Fleet Management
- [ ] [RC] Multi-node discovery via WireGuard mesh
- [ ] [RC] Centralized camera management dashboard
- [ ] [RC] Model distribution across fleet nodes
- [ ] [RC] Aggregated analytics from all nodes
- [ ] [RC] Remote configuration updates

## [RC] CLI & Infrastructure
- [ ] [RC] hailo-vision CLI tool
- [ ] [RC] systemd service files for daemon mode
- [ ] [RC] Docker image with Hailo runtime
- [ ] [RC] Landing page deployment to hailo.blackroad.io
- [ ] [RC] CI/CD pipeline for model compilation
