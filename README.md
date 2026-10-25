# MedlarTV Commands

Public catalog of MedlarTV chat commands:
https://DevilMedlar.github.io/medlar-commands-site/

The files in `docs/` are currently a generated static snapshot based on the
MedlarTV command configuration and implemented dispatch metadata. They do not
update automatically when the source changes yet.

**Future goal:** after the Command Center and related features are complete,
changes to the command configuration and implemented features should flow
automatically to the published catalog. That integration is not implemented;
the trigger and publishing behavior still need to be designed and verified.

To regenerate the catalog from the MedlarTV source checkout, run:

```bat
update-commands-site.bat --public-repo "C:\path\to\medlar-commands-site"
```

This regenerates the catalog files but does not publish them. Add `--publish`
only when you intend to push the generated update; this manual step is the
current workflow, not the future automatic-update goal.
