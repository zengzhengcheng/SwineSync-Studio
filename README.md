# SwineSync Studio

Public release repository for the packaged desktop build of `SwineSync Studio`.

This repository is for **binary distribution** rather than open-source code hosting.

## Related Repository

- Open-source companion repository: [SwineSync-OpenSource](https://github.com/zengzhengcheng/SwineSync-OpenSource)
- Public packaged-release repository: [SwineSync-Studio](https://github.com/zengzhengcheng/SwineSync-Studio)

## What To Download

Users should download the following release assets from the Releases page:

- `main.exe`
- `trabase_model.onnx.enc`
- `tragan_model.onnx.enc`
- `traganbase_model.onnx.enc`
- `first.obj`

The empty placeholder file below is provided directly in the repository:

- `release_layout/userModels/初始模型.obj`

## Required Folder Layout

After downloading, place the files in the following structure:

```text
SwineSync-Studio/
|-- main.exe
|-- models/
|   |-- trabase_model.onnx.enc
|   |-- tragan_model.onnx.enc
|   `-- traganbase_model.onnx.enc
`-- userModels/
    |-- first.obj
    `-- 初始模型.obj
```

## Important Notes

- The first run may be flagged or removed by antivirus software. Users should be warned in advance.
- The software requires network access on the first run.
- The software requires network access once every 10 launches.
- Once the software has been run, its filesystem location should not be moved.
- If the user moves the software to another location, they should re-download it.
- If multiple parallel copies are needed, users should download separate copies into different filesystem locations.
- This packaged build stops working after `2027-05-05`.
- The expiration date will be updated whenever a new version is released.
- This is intended to encourage users to keep using the latest version of the software, because new releases will continue to include new features, improvements, and fixes.

## Scope

This repository only distributes the packaged application files.

- It does not serve as the primary source-code repository.
- The open-source processing code is maintained in `SwineSync-OpenSource`.
