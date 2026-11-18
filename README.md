## Roadmap

### Task 0 - Install Lerobot
- *Due date*: 09/11/2026-13/11/2026
- Resources: [Lerobot installation tutorial](https://huggingface.co/docs/lerobot/main/en/installation)

Install Lerobot by following the tutorial above.
*Notes:* at [Step 3](https://huggingface.co/docs/lerobot/main/en/installation#step-3-install-lerobot-) choose [Installation from PyPi](https://huggingface.co/docs/lerobot/main/en/installation#installation-from-pypi).

Of all the listed optional commands just run `pip install 'lerobot[all]'`.

### Task 1 - Run teleop
- *Due date*: 11/11/2026
- Resources: [Lerobot teleop tutorial](https://huggingface.co/docs/lerobot/main/en/il_robots)
- Goal: run the following chapters [Set up and Calibrate](https://huggingface.co/docs/lerobot/main/en/il_robots), [Teleoperate](https://huggingface.co/docs/lerobot/main/en/il_robots), [Cameras](https://huggingface.co/docs/lerobot/main/en/il_robots), [Teleoperate with cameras](https://huggingface.co/docs/lerobot/main/en/il_robots)

### Task 2 - LeLab, cameras and first policy on the real robot
- *Due date*: 18/11/2026
- Resources: [LeLab docs](https://huggingface.co/docs/lerobot/main/en/lelab#features), [Lerobot teleop tutorial](https://huggingface.co/docs/lerobot/il_robots), [Cameras tutorial](https://huggingface.co/docs/lerobot/cameras), [cubo_arancione_100 policy](https://huggingface.co/AEA-HF/cubo_arancione_100)
- Goal:
  1. **Install LeLab** by following the [LeLab docs](https://huggingface.co/docs/lerobot/main/en/lelab#features), then run teleoperation from it.
  2. **Set up the cameras** by following the camera sections of last week's [teleop tutorial](https://huggingface.co/docs/lerobot/il_robots) (more detail in the [Cameras tutorial](https://huggingface.co/docs/lerobot/cameras)). Then run teleop with cameras, either from the CLI or from LeLab, to check that they work.
  3. **Run a policy on the real robot**: use LeLab to deploy [AEA-HF/cubo_arancione_100](https://huggingface.co/AEA-HF/cubo_arancione_100).
