# Quan Tran

First-year professional master's student at Mila and Université de Montréal. I work on machine learning and robotics.

## Selected work

| Project | What it does | Stack |
|---|---|---|
| [dancing-with-sars](https://github.com/benhoangquan/dancing-with-sars) | Scrollytelling site built on NASA-ISRO NISAR radar data for the 2026 NASA Space Apps Challenge. Measures radar backscatter inside four wildfire perimeters (HV 0.8 to 1.0 dB below the surrounding land) and a deforestation site in Rondônia (374 ha cleared, 6.0 dB mean HV drop). | Python, Cloud-Optimized GeoTIFF, Next.js, MapLibre, deck.gl |
| [ey_challenge_2026](https://github.com/benhoangquan/ey_challenge_2026) | Predicts water quality from Landsat bands, TerraClimate, elevation and flow accumulation. Random forest with location-grouped 5-fold CV: R² 0.25 (total alkalinity), 0.36 (electrical conductance), 0.10 (dissolved reactive phosphorus). | scikit-learn, Google Earth Engine, SLURM |
| [voice-bot](https://github.com/benhoangquan/voice-bot) | Real-time voice agent for restaurant reservations. One Pipecat pipeline runs speech-to-text, Claude and text-to-speech, with tool calls for menu search (ChromaDB), booking and handoff to staff, plus rate-limit and abuse guardrails. | Pipecat, Deepgram, ElevenLabs, Daily, FastAPI |
| [hvac-demand-forecasting](https://github.com/benhoangquan/hvac-demand-forecasting) | LSTM that forecasts a Montreal house's HVAC load 4 hours (16 steps) ahead. Five-seed bagged ensemble, tracked with MLflow. Kaggle score 0.35333. | PyTorch, MLflow |
| [swarm-alignment-2026](https://github.com/Nas01010101/swarm-alignment-2026) | Paper and code on whether rules or ownership get 100 LLM agents (Gemma 4 26B) to build a shared wall. An elected quota-setter keeps 36.6 of 100 agents alive on average, laissez-faire keeps 5.0. First author, with three teammates. | Python, Minecraft (Mineflayer), LLM agents |
| [khp-guardrail-hackathon](https://github.com/benhoangquan/khp-guardrail-hackathon) | English and French triage guardrail for youth mental-health chat, built for the Mila x Bell x Kids Help Phone hackathon. A drift diffusion model over the conversation is blended with an LLM judge: F1 0.850 at 1,103 ms per sample on the organizers' test set. Team of five. | Python, LLM judge, drift diffusion model |

## Contact

[qmtl.dev](https://qmtl.dev) · [LinkedIn](https://www.linkedin.com/in/benhoangquan) · hoangquan.tran410@gmail.com
