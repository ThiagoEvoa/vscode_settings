
# vscode_settings

## settings.json

```json
{
    "dart.renameFilesWithClasses": "prompt",
    "dart.previewFlutterUiGuides": true,
    "[dart]": {
        "editor.formatOnSave": true,
        "editor.formatOnType": true,
        "editor.codeActionsOnSave": {
            "source.organizeImports": "explicit",
            "source.fixAll": "explicit",
        },
        "editor.defaultFormatter": "Dart-Code.dart-code"
    },
    "[dart][typescript]": {
        "editor.codeActionsOnSave": {
            "source.organizeImports": "explicit",
            "source.fixAll": "explicit"
        }
    },
    "[typescript]": {
        "editor.formatOnSave": true,
        "editor.formatOnType": true,
        "editor.codeActionsOnSave": {
            "source.organizeImports": "explicit",
            "source.fixAll": "explicit",
        },
        "editor.defaultFormatter": "vscode.typescript-language-features"
    },
    "explorer.fileNesting.enabled": true,
    "explorer.fileNesting.expand": false,
    "explorer.fileNesting.patterns": {
        "pubspec.yaml": "pubspec.lock,pubspec_overrides.yaml,.packages,.flutter-plugins,.flutter-plugins-dependencies,.metadata",
        "*.dart": "${capture}.g.dart, ${capture}.freezed.dart"
    },
    "editor.cursorBlinking": "phase",
    "editor.cursorSmoothCaretAnimation": "on",
    "editor.bracketPairColorization.enabled": true,
    "editor.stickyScroll.enabled": true,
    "editor.inlineSuggest.enabled": true,
    "workbench.startupEditor": "none",
    "workbench.colorTheme": "GitHub Dark Colorblind (Beta)",
    "window.restoreWindows": "none",
    "redhat.telemetry.enabled": false,
    "codesnap.showLineNumbers": true,
    "codesnap.showWindowControls": true,
    "codesnap.showWindowTitle": true,
    "codesnap.transparentBackground": true,
    "git.openRepositoryInParentFolders": "never",
    "git.enableSmartCommit": true,
    "githubPullRequests.notifications": "pullRequests",
    "githubPullRequests.queries": [
        {
            "label": "Waiting For My Review",
            "query": "is:open review-requested:${user}"
        },
        {
            "label": "Assigned To Me",
            "query": "is:open assignee:${user}"
        },
        {
            "label": "Created By Me",
            "query": "is:open author:${user}"
        },
        {
            "label": "Mentioned Me",
            "query": "is:open mentions:${user}"
        },
        {
            "labes": "Waiting For Organization Review",
            "query": "is:open org-review-requested:${user}"
        },
        {
            "label": "Waiting For Team Review",
            "query": "is:open team-review-requested:${user}"
        }
    ],
}
```


## Extension ID's

- Codeium.codeium
- adpyke.codesnap
- Dart-Code.dart-code
- hzgood.dart-data-class-generator
- usernamehw.errorlens
- Dart-Code.flutter
- robert-brunhage
- flutter-riverpod-snippets
- alexisvt.flutter-snippets
- github.vscode-github-actions
- GitHub.vscode-pull-request-github
- GitHub.remotehub
- GitHub.github-vscode-theme
- eamodio.gitlens
- ms-vsliveshare.vsliveshare
- lottiefiles.vscode-lottie
- Postman.postman-for-vscode
- jeroen-meijer.pubspec-assist
- ms-vscode.remote-repositories
- pflannery.vscode-versionlens
- redhat.vscode-yaml
