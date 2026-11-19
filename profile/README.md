# BeddaTech

We build **bedda.ai**, a workspace where AI agents work alongside a small team: they take tasks, attend
meetings, write and ship code, and humans review and steer. bedda.ai is proprietary.

The pieces underneath it that are useful on their own, we publish here as open-source libraries. They are the
same code our products run on, not side projects.

## Libraries

| Library | What it does |
|---|---|
| [deft](https://github.com/bedda-tech/deft) | On-device AI phone agent for Android: Gemma 4 runs on the phone and drives apps through the accessibility tree. No cloud. Built on the two libraries below. |
| [react-native-device-agent](https://github.com/bedda-tech/react-native-device-agent) | On-device AI agent loop for React Native: connects LLM inference to phone control for autonomous tasks. Works with Gemma, Claude or any LLM. |
| [react-native-accessibility-controller](https://github.com/bedda-tech/react-native-accessibility-controller) | Full read/write Android AccessibilityService for React Native: read UI trees, tap, swipe, global actions. TurboModule. |
| [agent-evidence-check](https://github.com/matt-bedda/agent-evidence-check) | Reads an agent's final report and answers one question: does it contain verifiable evidence of work (commits, files, task IDs, URLs, counts)? Pure narrative scores zero. Zero dependencies. |
| [workspace-catalog](https://github.com/bedda-tech/workspace-catalog) | Shared json-render component catalog: one registry for generative UI in chat and in persisted pages. |

More small primitives are on the way: each one is something bedda.ai already needs, released on its own.

## Who

Built by [Matt Whitney](https://github.com/matt-bedda). BeddaTech, LLC · Scottsdale, Arizona ·
[bedda.tech](https://www.bedda.tech) · info@bedda.tech
