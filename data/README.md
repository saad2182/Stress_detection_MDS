# Local subject datasets

The local working copy contains four HDF5 files derived from subjects 21, 28, 29, and 31. They are intentionally excluded from Git by `.gitignore` because they contain human-participant sensor measurements and the source archive did not include a public data-use license.

Expected local filenames:

```text
subject-21.h5
subject-28.h5
subject-29.h5
subject-31.h5
```

The historical classification notebook expects names such as `data21.h5` in its current working directory. Either copy an authorized dataset beside the notebook under that name or update the notebook's `load_data` and `pick_session_data` filename construction to point here.

Do not publish these files until their consent, IRB, lab, and institutional sharing requirements are confirmed.
