#  RL-Driven Carbon-Aware Serverless Scheduler

An intelligent cloud scheduling platform that reduces carbon emissions by using Reinforcement Learning (RL) to make environmentally aware scheduling decisions for serverless workloads.

## Overview

Traditional cloud schedulers focus primarily on performance and resource utilization. This project introduces a carbon-aware scheduling approach that considers the environmental impact of workload execution.

The scheduler continuously monitors carbon intensity across cloud regions and uses Reinforcement Learning to determine the most sustainable execution location and timing for serverless tasks.

For delay-tolerant workloads, the system can postpone execution until cleaner energy sources become available, reducing overall carbon emissions while maintaining acceptable performance.

## Key Features

* Reinforcement Learning-based scheduling decisions
* Carbon-aware workload placement
* Multi-region cloud support
* Renewable energy utilization optimization
* Delay-tolerant task scheduling
* Performance and latency-aware execution
* Real-time decision engine
* Interactive monitoring dashboard

## System Architecture

### Components

#### Frontend Dashboard

* Real-time monitoring interface
* Scheduling visualization
* Carbon savings metrics
* Job execution tracking

#### Backend Engine

* Carbon intensity monitoring
* Scheduling decision engine
* API integration layer
* Workload management

#### Reinforcement Learning Agent

* Learns optimal scheduling strategies
* Balances performance and sustainability
* Adapts to changing energy conditions

## Project Structure

```text
CARBON-AWARE RL SCHEDULER/
│
├── backend/
├── carbon_aware_scheduler/
├── scheduler_app/
├── frontend/
├── data/
├── requirements.txt
├── manage.py
└── PROJECT_REPORT.md
```

## Installation

### Clone Repository

```bash
git clone https://github.com/your-username/rl-carbon-aware-scheduler.git
cd rl-carbon-aware-scheduler
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Environment

Windows:

```bash
venv\Scripts\activate
```

Linux/Mac:

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

## Run Application

```bash
python manage.py runserver
```

Open:

```text
http://127.0.0.1:8000
```

## Expected Benefits

* Reduced cloud carbon footprint
* Improved energy efficiency
* Sustainable cloud operations
* Intelligent workload management
* Support for green computing initiatives

## Future Enhancements

* Real-time carbon intensity APIs
* Multi-cloud provider integration
* Advanced Deep Reinforcement Learning models
* Predictive renewable energy forecasting
* Automated workload migration

## Technologies Used

* Python
* Django
* Reinforcement Learning
* Pandas
* NumPy
* JavaScript
* HTML/CSS

## Author

Developed as a research and sustainability-focused cloud computing project exploring AI-driven carbon-aware scheduling for modern cloud infrastructure.
