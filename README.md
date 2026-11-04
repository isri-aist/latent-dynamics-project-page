# Online Adaptation project page

Static project page for “Online Adaptation to Latent Physical Properties for Learning from Demonstration.” Open `index.html` directly or serve this directory with `python3 -m http.server 8000`.

## Structure and media sources

- `index.html` and `style.css` contain the page and responsive layout. `AGENTS.md` documents contributor conventions.
- `assets/online-adaptation-paper.pdf` is the supplied SII 2027 submission manuscript (`root.pdf`). Venue and publication details are not confirmed; the page links the local PDF and labels external video publication as coming soon.
- `assets/images/approach-overview.png`, `training-deployment-pipeline.png`, and `simulation-results.png` are manuscript figures (`ConceptNew.png`, `ProposedPipeline.png`, and `SimulationSuccessRate.png`). The simulation chart's top frame is spaced farther from its 96.7 value label for legibility.
- `assets/images/figure-5-real-world-success-rates.png` is a crop of Figure 5 on page 8 of the supplied manuscript, presenting real-robot success rates.
- `assets/images/dynamics-model-evaluation.png` is the dynamics-model evaluation figure from page 7, cropped without its printed figure number and caption.
- `assets/videos/simulation/experiments-task-setup.mp4` is an 18.018 s crop from 40–58 s in `まとめ_video完成.mp4`. It preserves the animated Pouch Placement, Box Pushing, and Horizontal Lifting task panels while cropping off the explanatory sentence at the bottom. Its poster is `assets/images/experiments-task-setup-poster.jpg`.
- `assets/videos/research-overview.mp4` is a copy of `Kajitsuka_SII2027_video.mp4` from `LatentDynamicsVideoSource/FutureImaginationVideo/FutureImagination/final_papar_and_presentation_slides/` (121.9 s, 1920×1080). The page uses its opening frame as the poster and requires a click to play.

## Embedded task videos

- `assets/videos/rollouts/pouch-placement-dp-failure.mp4` is an unmarked 11.4 s version of the Pouch Diffusion Policy failure video, shortened from the supplied 2× source by cutting its ending. Pouch result videos do not mark weight positions.
- `assets/videos/rollouts/pouch-vae-future-reconstruction.mp4` is copied from `~/my_projects/robot/RoboManipBaselines/robo_manip_baselines/dataset_rmb_2026_10_20/tests/FutureImaginationReal/Pouch/constant/seed62/far/WrenchPredObject2/Pouch_constant_normal_world0_004.rmb/Pouch_constant_normal_world0_004_right_online_pb_reconstruction.mp4`. It shows the right-camera image and online predicted/reconstructed images at horizon 16 (about 1.5 s). The video and poster have no weight-position overlay.
- `assets/videos/rollouts/box-pushing-baseline-failure.mp4` and `box-pushing-proposed.mp4` are copies of paired 2× videos from `final_papar_and_presentation_slides/video用素材/BoxPushing/`. The corresponding `*-marked.mp4` page versions prepend a 2.5 s still and weight-position marker based on the comparison slide in `まとめ_video完成.mp4` (about 90 s); the marker was shifted about 15 px left and the label centered. Original copied videos are kept unchanged. Captions identify the baseline failure from its source label and do not assert an outcome for the proposed video.
- `assets/videos/simulation/online-adaptation-final-slide.mp4` is the final visualization sequence extracted from 105 s to the end of `まとめ_video完成.mp4` (20.031 s). It shows simulated rollout video alongside online parameter estimation; poster: `assets/images/online-adaptation-final-slide.jpg`.
- `assets/images/figure-5-real-world-success-rates.png` is tightly cropped around the plot and axis labels to avoid blank margins.

The research overview video remains click-to-play; supporting videos autoplay muted and loop with controls available. Generated page versions were written separately from their source files. Results for PushingLine Object 0 and Object 4 are intentionally omitted. When adding or editing media, record its source, edits, and what is visible here; inspect playback and representative frames before publishing.
