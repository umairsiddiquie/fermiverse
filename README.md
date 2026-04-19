# fermiverse

FermiVerse/
├── 📁 docs/
│   ├── DESIGN.md                # Tri-domain architecture
│   ├── QUANTUM_NOTATION.md    # Dirac + fermion formalism
│   ├── DETONANCE_SONNETS.md   # All sonnets + det proofs
│   └── CHI_SUBMISSION.md      # Full paper draft
├── 📁 src/
│   ├── python/
│   │   ├── fermiverse_notation.py     # Main PyGame app
│   │   ├── fermiverse_vr_stub.py      # VR pose emitter
│   │   ├── umairsiddiquiepoetry/
│   │   │   ├── model.py
│   │   │   ├── constraint.py         # DeterminantLoss, FermionGuard
│   │   │   ├── export_onnx.py
│   │   │   └── infer.py
│   │   └── utils/
│   │       ├── sonify.py             # Unified audio engine
│   │       └── dependency_parser.py
│   └── web/
│       ├── index.html               # Tone.js demo
│       ├── fermiverse.js            # p5 + Tone integration
│       └── assets/
│           └── sounds/              # .wav stems for det=0, det=1, etc.
├── 📁 notebooks/
│   ├── sonnet_generation.ipynb
│   ├── det_verification.ipynb      # Symbolic det calc
│   └── user_study_analysis.ipynb
├── 📁 data/
│   ├── sonnets_det1.json           # 500 validated poems
│   ├── incidence_matrices/         # .npy files
│   └── vr_pose_stream/             # Simulated HMD logs
├── 📁 tests/
│   ├── test_determinant.py
│   └── test_fermion_guard.py
├── 📄 LICENSE                     # CC-BY-4.0
├── 📄 CODE_OF_CONDUCT.md
├── 📄 CONTRIBUTING.md
├── 📄 pyproject.toml              # Poetry setup
├── 📄 Dockerfile                  # For reproducible env
└── 📄 README.md                   # Hero: "GAME THEORY: Where every poem is a winning strategy"
