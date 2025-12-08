---
layout: default
title: Projects
---
{% include navbar.html %}

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

<div class="page-content">
  <h2>Projects</h2>
  
  <div class="project-grid">
    <div class="project-card">
      <div class="project-icon">
        <i class="fas fa-walking"></i>
      </div>
      <h3>Soft Knee Exoskeleton</h3>
      <span class="project-badge">Master's Thesis • 2025</span>
      <p>Developing a compact soft automated knee exoskeleton for walking assistance using twisted elastic actuators (TEAs) that mimic human muscle actuation.</p>
      <p><strong>Technologies:</strong> Soft Robotics, TEAs, Biomechanics</p>
    </div>
    
    <div class="project-card">
      <div class="project-icon">
        <i class="fas fa-wheelchair"></i>
      </div>
      <h3>Robotic Exoskeleton for Knee Disabilities</h3>
      <span class="project-badge">Patent ID: 424311-001 • 2024</span>
      <p>Devised a compact and affordable exoskeleton for disabilities from knee hyperextension and foot drop using twisted coiled polymers (TCPs) and electromagnetic clutch.</p>
      <p><strong>Technologies:</strong> CNN, AdaBins, Soft Actuators</p>
    </div>

    <div class="project-card">
      <div class="project-icon">
        <i class="fas fa-car"></i>
      </div>
      <h3>Driving Perception System</h3>
      <span class="project-badge">WPI • 2024</span>
      <p>Developed an autonomous 3D visualization system for vehicles with detection of vehicles, lanes, and road signs on real-time dashcam video data.</p>
      <p><strong>Technologies:</strong> YOLO, YOLO3D, Detic, EasyOCR, Masked RCNN, DepthAnything, Blender</p>
      <a href="https://github.com/RheaBhalekar24" class="project-link">View on GitHub →</a>
    </div>

    <div class="project-card">
      <div class="project-icon">
        <i class="fas fa-robot"></i>
      </div>
      <h3>Manipulation & Environmental Robotics Lab</h3>
      <span class="project-badge">Directed Research • 2024</span>
      <p>Deployed a Panda arm for grasping objects in cluttered environments with ResUNet14 and Nvidia's Minkowski Engine integrated into ROS2 pipeline.</p>
      <p><strong>Technologies:</strong> ROS2, ResUNet14, Minkowski Engine</p>
    </div>

    <div class="project-card">
      <div class="project-icon">
        <i class="fas fa-ship"></i>
      </div>
      <h3>Hyacinth Weed Collector Robot</h3>
      <span class="project-badge">Mumbai • 2024</span>
      <p>Engineered a semi-autonomous robot with high-torque motors for efficient collection and crushing of hyacinth weed in lakes using computer vision.</p>
      <p><strong>Technologies:</strong> Image Processing, Random Walk Algorithm, OpenCV</p>
    </div>

    <div class="project-card">
      <div class="project-icon">
        <i class="fas fa-music"></i>
      </div>
      <h3>Music Generation using Vanilla GANs</h3>
      <span class="project-badge">WPI • 2024</span>
      <p>Implemented a Generative Adversarial Network to generate synthetic music data using the MIDI dataset with generator-discriminator architecture.</p>
      <p><strong>Technologies:</strong> GANs, Deep Learning, PyTorch, MIDI</p>
    </div>

    <div class="project-card">
      <div class="project-icon">
        <i class="fas fa-hard-hat"></i>
      </div>
      <h3>Smart Suit for Mine Workers</h3>
      <span class="project-badge">Smart India Hackathon Qualifier • 2021</span>
      <p>Created a smart sensor suit with gas sensors and nRF24L01 communication network for hazardous mine environments.</p>
      <p><strong>Technologies:</strong> IoT, Sensor Networks, Embedded Systems</p>
    </div>

    <div class="project-card">
      <div class="project-icon">
        <i class="fas fa-x-ray"></i>
      </div>
      <h3>Autoencoder for Denoising X-Ray Data</h3>
      <span class="project-badge">Mumbai • 2024</span>
      <p>Programmed a denoising autoencoder to enhance tooth X-ray images by reducing noise and improving diagnostic clarity.</p>
      <p><strong>Technologies:</strong> Autoencoders, TensorFlow, Image Processing</p>
    </div>

    <div class="project-card">
      <div class="project-icon">
        <i class="fas fa-trophy"></i>
      </div>
      <h3>ABU Robocon Competition</h3>
      <span class="project-badge">National Level • 2022-2023</span>
      <p>Competed at national levels designing robots for Lagori (2022) and throwing flowers over Angkor Wat (2023). Achieved 18th place nationally in 2022.</p>
      <p><strong>Technologies:</strong> SOLIDWORKS, Arduino, Embedded Systems</p>
    </div>
  </div>
</div>

<style>
.page-content {
  max-width: 1200px;
  margin: 3rem auto;
  padding: 0 2rem;
}

.page-content h2 {
  color: #667eea;
  text-align: center;
  font-size: 2.5rem;
  margin-bottom: 3rem;
}

.project-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
  gap: 2rem;
  margin-top: 2rem;
}

.project-card {
  background: #fff;
  padding: 2rem;
  border-radius: 12px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
  transition: all 0.3s ease;
  border-top: 4px solid #667eea;
}

.project-card:hover {
  transform: translateY(-8px);
  box-shadow: 0 8px 24px rgba(102,126,234,0.2);
}

.project-icon {
  width: 60px;
  height: 60px;
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  border-radius: 12px;
  display: flex;
  align-items: center;
  justify-content: center;
  margin-bottom: 1.5rem;
}

.project-icon i {
  font-size: 1.8rem;
  color: white;
}

.project-card h3 {
  color: #333;
  margin-top: 0;
  margin-bottom: 0.5rem;
  font-size: 1.3rem;
}

.project-badge {
  display: inline-block;
  background: #f0f0f0;
  color: #667eea;
  padding: 0.25rem 0.75rem;
  border-radius: 20px;
  font-size: 0.85rem;
  font-weight: 500;
  margin-bottom: 1rem;
}

.project-card p {
  color: #666;
  line-height: 1.6;
  margin-bottom: 1rem;
}

.project-link {
  color: #667eea;
  text-decoration: none;
  font-weight: 600;
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  margin-top: 1rem;
}

.project-link:hover {
  color: #764ba2;
  text-decoration: underline;
}

@media (max-width: 768px) {
  .project-grid {
    grid-template-columns: 1fr;
  }
}
</style>
