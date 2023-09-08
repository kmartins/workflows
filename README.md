# Workflows - Dart and Flutter

[![ci][ci_badge]][ci_link]
[![License: MIT][license_badge]][license_link]

Reusable [Github Workflows][github_workflows] used in my **Dart/Flutter packages** and the **apps**.

It's a copy of the [very good workflows][very_good_workflows], but with de some other `workflows` and some different `actions`.

## Here we go

Workflow for Dart packages
```yaml
uses: kmartins/workflows/.github/workflows/dart_package.yaml@v1
```

Workflow for Flutter packages
```yaml
uses: kmartins/workflows/.github/workflows/flutter_package.yaml@v1
```

Workflow for verifying package score on the [pub.dev][pub]
```yaml
uses: kmartins/workflows/.github/workflows/pana.yaml@v1
```

Workflow for publish your package on the [pub.dev][pub]
```yaml
uses: kmartins/workflows/.github/workflows/pub_publish.yaml@v1
```

Workflow for your Flutter app - Works with the Firebase
```yaml
uses: kmartins/workflows/.github/workflows/flutter_app.yaml@v1
```

Workflow for building your Flutter app (There are no check formatting, analysis, and test) - Works with the Firebase
```yaml
uses: kmartins/workflows/.github/workflows/build_flutter_app.yaml@v1
```

Workflow for ensuring `pull request` title is semantic - [Angular Convention][angular_convention]
```yaml
uses: kmartins/workflows/.github/workflows/semantic_pull_request.yaml@v1
```

> Look at the `workflow` files to know what `inputs` are available.</br>
> `Workflows` for the **flutter app** work when **firebase files** are not present in the repository.

## What are the next steps?

- [X] Publish **Dart** and **Flutter** `package` on the [pub.dev][pub]
- [ ] Publish the **Android** app on the [Play Store][play_store]
- [ ] Publish the **iO**S app on the [App Store][app_store]
- [ ] Publish the **macOS** app on the [App Store][app_store]
- [ ] Deploy **Web** app on the [Firebase Hosting][firebase_hosting]  
- [X] Firebase Services - [Functions][firebase_functions] and [Firestore][firebase_firestore]

## 📝 Maintainers

[Kauê Martins][github_profile]

## 🤝 Support

Did you like this package? Then give it a ⭐️. If you want to help then:

- **Fork** this repository
- Send a **Pull Request** with a new `workflow`
- Share these `workflows`
- Create **issues** if you find a **bug** or want to **suggest** a new `workflow`

[ci_badge]: https://github.com/kmartins/workflows/actions/workflows/ci.yaml/badge.svg
[ci_link]: https://github.com/kmartins/workflows/actions
[license_badge]: https://img.shields.io/badge/license-MIT-blue.svg
[license_link]: https://opensource.org/licenses/MIT
[github_workflows]: https://docs.github.com/en/actions/using-workflows/workflow-syntax-for-github-actions
[very_good_workflows]: https://github.com/VeryGoodOpenSource/very_good_workflows
[pub]: https://pub.dev/
[angular_convention]: https://github.com/angular/angular/blob/22b96b9/CONTRIBUTING.md#-commit-message-guidelines
[firebase_hosting]: https://firebase.google.com/docs/hosting
[play_store]: https://developer.android.com/studio/publish
[app_store]: https://developer.apple.com/app-store/submitting/
[firebase_functions]: https://firebase.google.com/products/functions
[firebase_firestore]: https://firebase.google.com/products/firestore
[github_profile]: https://github.com/kmartins
