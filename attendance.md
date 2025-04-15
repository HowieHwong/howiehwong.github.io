---
layout: normal
title: Attendance
---

<style>
.attendance-container {
  max-width: 800px;
  margin: 40px auto;
  padding: 30px;
  background: linear-gradient(to right, #fdfde7, #f5f5f5);
  border: 1px solid #ccc;
  border-radius: 8px;
  box-shadow: 0 4px 16px rgba(0,0,0,0.1);
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

.attendance-container h2 {
  text-align: center;
  margin-bottom: 20px;
  color: #333;
}

.attendance-list {
  list-style: none;
  padding: 0;
}

.attendance-list li {
  margin-bottom: 15px;
  padding: 15px;
  background-color: #ffffff;
  border-left: 5px solid #007acc;
  box-shadow: 0 2px 4px rgba(0,0,0,0.05);
  transition: background-color 0.3s;
}

.attendance-list li:hover {
  background-color: #f0f8ff;
}

.attendance-list li s {
  color: #999;
}

.attendance-list .event-title {
  font-weight: bold;
  font-size: 1.1em;
  color: #007acc;
}

.attendance-list .event-date,
.attendance-list .event-location {
  display: block;
  font-size: 0.95em;
  color: #555;
  margin-top: 5px;
}
</style>

<div class="attendance-container">
  <h2>Conference & Event Attendance</h2>
  <ul class="attendance-list">
    <li>
      <s>
        <span class="event-title">EMNLP 2024</span>
        <span class="event-date">November 12–16, 2024</span>
        <span class="event-location">Miami, Florida, USA</span>
      </s>
    </li>
    <li>
      <s>
        <span class="event-title">NeurIPS 2024</span>
        <span class="event-date">December 10–15, 2024</span>
        <span class="event-location">Vancouver, Canada</span>
      </s>
    </li>
    <li>
      <s>
        <span class="event-title">KAUST AI Rising Stars Symposium 2025</span>
        <span class="event-date">April 7–10, 2025</span>
        <span class="event-location">Thuwal, Saudi Arabia</span>
      </s>
    </li>
    <li>
      <span class="event-title">Midwest Speech and Language Days (MSLD) 2025</span>
      <span class="event-date">April 15–16, 2025</span>
      <span class="event-location">University of Notre Dame, Indiana, USA</span>
    </li>
  </ul>
</div>
