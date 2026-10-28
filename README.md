## Hi, I'm Bin 👋

People and AI are starting to work side by side, and much of my own work is now done together with AI agents. I keep finding that it goes best when the agent and I understand the same thing at the same time. So I've been building a few small tools to help people and AI work in parallel and look at the same picture.

### Two tools for working alongside AI

Both started from my own days of running several coding agents at once and losing track of what each one had done.

- **[Trace Canvas](https://github.com/CallSymmetryEcho/trace-canvas)** keeps track of *what happened*. Every agent session becomes a line on one transit map, with instructions, edits, commits and decisions as its stations. I read the map to see how the parallel work fits together, and the agents read the same map to pick up where another one left off.
- **[Theatrum](https://github.com/CallSymmetryEcho/Theatrum)** keeps track of *what was learned*. It is a shared memory kept as plain Markdown: agents write down what they figured out, any agent can recall it later, and I can open the same files to read or correct them.

In both, the person and the agents work from one shared record. Both are early, and issues and ideas are very welcome.

### Background

I'm a Ph.D. candidate at UT Austin, and I finished my degree in Materials Physics at USTC.

### A few projects I'm happy with

- **A tomographic 3D printer (USTC).** A light-curing printer based on the volumetric printing work of Kelly et al. (*Science*, 2019). It led to my first paper.
- **A hydrogel-sensor glove.** A wireless glove whose hydrogel strain sensors read finger motion. A CNN-LSTM decoder turns that motion into commands for an electric tweezer, so a hand can steer a nanowire directly. Using both hands, it supports multi-scale manipulation, from fine micro-scale moves to travel over about 1 cm.
- **An sEMG wristband.** With a small team, I built an 8-channel muscle-signal and IMU band on a Jetson Orin Nano that controls a computer and a drone with hand gestures. I led the engineering work and wrote the gesture decoders.
- **AlchemArm.** A 3D-printed four-axis SCARA arm for the hydrofluoric-acid step of metal-assisted etching. It has dipped and retrieved its first chip carrier in HF inside a fume hood.
- **A reinforcement-learning controller for electric tweezers.** I wrote a Langevin digital twin of a nanowire trap and trained policies in it. In simulation, a learned planner reached the goal around obstacles in 66% of layouts, against 4% for PID. Moving it onto the real setup is next.

The code for these is not public yet.

I'm especially interested in physical AI, where AI works with real instruments and materials, not only with text and code. I'd like to help people and AI agents share the same view of an experiment (the simulation, the sensor signals and the record of what happened) before deciding together what the hardware does next.

Outside the lab, I practice fingerstyle guitar (slowly), look for good food around Austin, and self-host more services on a home NAS than is probably reasonable.

### Elsewhere

- Homepage: [bin-lian.me](https://bin-lian.me/)
- Blog, mostly in Chinese, with notes on tools and things I'm learning: [callsymmetryecho.github.io](https://callsymmetryecho.github.io/)
- LinkedIn: [Bin Lian](https://www.linkedin.com/in/jakie-2843041bb/)
- Email: bin_lian [at] utexas [dot] edu
