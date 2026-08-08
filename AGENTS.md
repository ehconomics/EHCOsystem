# EHCO Assistant Entry Point

This repository inherits the accepted EHCO organization assistant control from `EHCOnomics-Systems/EHCO@401e1283ebe5840896981f54e06b36a16b7dfc13`. It applies to every assistant/model/provider/interface used for governed development. Local instructions may tighten it but may not weaken or bypass it.

Before changing source, read `ehco.repository.yaml`, `ehco.operation.yaml`, and the pinned canonical protocol/schema. Treat the selected operation as the work unit: complete dependent in-scope steps; diagnose, correct, and reverify failures; run appropriate regression; reconcile evidence and cleanup; do not request redundant approval for already-authorized in-scope actions; and stop only at a real boundary not already authorized.

```text
EHCO_EXECUTION_CONTINUITY_V1
MODEL_SCOPE=ALL_ASSISTANT_MODELS
WORK_UNIT=SELECTED_OPERATION_CHAIN
DEPTH_POLICY=COMPLETE_DEPENDENT_STEPS_WITHIN_SCOPE
FAILURE_POLICY=DIAGNOSE_CORRECT_REVERIFY_CONTINUE
INTRA_SCOPE_REAPPROVAL=NOT_REQUIRED
CLEANUP_POLICY=RECONCILE_OPERATIONAL_DEBRIS_BEFORE_COMPLETE
STOP_POLICY=REAL_SCOPE_AUTHORITY_SAFETY_OR_OWNER_BOUNDARY_ONLY
LOCAL_OVERRIDE=MAY_TIGHTEN_NOT_WEAKEN
```

Access, tools, commits, checks, model capability, or historical approval do not create authority. Assistant output is not technical evidence. This public evidence repository remains a projection/evidence surface and does not become Runtime truth. Accepted EHCO standing remains **52/53**.
