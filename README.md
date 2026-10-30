# AutoFleet AI Guard

> GPU-accelerated physical AI fleet orchestration engine combining Nebius Cloud LLM reasoning with NVIDIA cuOpt for micro-second hazard rerouting.

Built for the **NVIDIA x Nebius Global AI Hackathon**.

---

## Inspiration
Autonomous delivery fleets and robotic rovers are scaling globally, but today’s logistics engines rely on static routing paths. When unexpected road hazards, severe weather, or temporary obstructions occur, legacy CPU solvers take seconds to recalculate trajectories for multiple active rovers—causing operational downtime, collision risks, and delays. We built **AutoFleet AI Guard** to bridge physical AI sensory understanding with instant micro-second path optimization.

## What It Does
AutoFleet AI Guard is an end-to-end autonomous fleet orchestration engine. It continuously processes visual and environmental telemetry using vision-language reasoning models to detect real-time obstacles. Upon hazard identification, it streams vehicle constraints into a parallelized GPU route solver to execute sub-millisecond rerouting without stopping active rovers.

## System Architecture

