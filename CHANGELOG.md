# Changelog


## 2023/03/22/04:42 roll back multi arch for now
**Impact on files:**
```
.github/workflows/publish.yml
```
Check commit: [roll back multi arch for now](https://github.com/cogentapps/chat-with-gpt/commit/68147135f89a2a76eea9fa59fb2a02a9b9900f46)
## 2023/03/20/19:11 Update publish.yml
**Impact on files:**
```
.github/workflows/publish.yml
```
Check commit: [Update publish.yml](https://github.com/cogentapps/chat-with-gpt/commit/1998a661f805669e6c81ea6c31eadfe9b7cbf75b)
## 2023/03/21/00:30 install git
**Impact on files:**
```
Dockerfile
```
Check commit: [install git](https://github.com/cogentapps/chat-with-gpt/commit/797296e0fe5d7d57e6834a7fd459f6ce3a289e33)
## 2023/03/21/00:26 install git
**Impact on files:**
```
Dockerfile
```
Check commit: [install git](https://github.com/cogentapps/chat-with-gpt/commit/d9b584c423b0871bb0b834cec6d6c775829e5677)
## 2023/03/21/00:22 add docker build timeout
**Impact on files:**
```
.github/workflows/publish.yml
```
Check commit: [add docker build timeout](https://github.com/cogentapps/chat-with-gpt/commit/14e727330860255c522ace326f5b019de0298129)
## 2023/03/21/00:11 speech recognition error handling & browser fixes
**Impact on files:**
```
app/package.json
app/src/components/input.tsx
```
Check commit: [speech recognition error handling & browser fixes](https://github.com/cogentapps/chat-with-gpt/commit/d7251e34dad16fc3480c3c15c70ec461ae6a3938)
## 2023/03/20/21:28 fix memo deps
**Impact on files:**
```
app/src/components/input.tsx
```
Check commit: [fix memo deps](https://github.com/cogentapps/chat-with-gpt/commit/9e10796b5a6cfdc44acdb0442abdea589b0c543b)
## 2023/03/20/21:03 fallback to whisper when speechrecognition is not available
**Impact on files:**
```
app/src/components/input.tsx
app/src/components/settings/user.tsx
app/src/speech-recognition-types.d.ts
app/src/speech-recognition-types.ts
```
Check commit: [fallback to whisper when speechrecognition is not available](https://github.com/cogentapps/chat-with-gpt/commit/6359c9f50dd71cc3ba39f6ae3552460d532d0f25)
## 2023/03/20/08:36 possible fix for speech recognition on android
**Impact on files:**
```
app/src/components/input.tsx
```
Check commit: [possible fix for speech recognition on android](https://github.com/cogentapps/chat-with-gpt/commit/1917bc19e0cb2be8903a70f6751378525a7a3e49)
## 2023/03/20/07:52 Update README.md
**Impact on files:**
```
README.md
```
Check commit: [Update README.md](https://github.com/cogentapps/chat-with-gpt/commit/ac2a40f3829346465295340d8c7a883bcec43f28)
## 2023/03/20/14:46 speech error handling & tweaks
**Impact on files:**
```
app/src/components/input.tsx
```
Check commit: [speech error handling & tweaks](https://github.com/cogentapps/chat-with-gpt/commit/ce63613bdf2e4d19459f66b8a570fc41b33dc46b)
## 2023/03/20/14:18 possible fix for delete button
**Impact on files:**
```
app/src/components/sidebar/recent-chats.tsx
```
Check commit: [possible fix for delete button](https://github.com/cogentapps/chat-with-gpt/commit/f0b22eff64390644293cdff2acaf3eff0f4f3997)
## 2023/03/20/14:14 better error messages
**Impact on files:**
```
app/src/chat-manager.ts
app/src/openai.ts
```
Check commit: [better error messages](https://github.com/cogentapps/chat-with-gpt/commit/da0d4844f183fce65974a611e28526459676e2be)
## 2023/03/20/14:13 update trimmer logic
**Impact on files:**
```
app/src/tokenizer/chat-history-trimmer.ts
```
Check commit: [update trimmer logic](https://github.com/cogentapps/chat-with-gpt/commit/746981ed9e6b7f31e4a0641e40f79deb2e59b281)
## 2023/03/20/06:06 Merge pull request #58 from tluyben/whisper-stt-api
Check commit: [Merge pull request #58 from tluyben/whisper-stt-api](https://github.com/cogentapps/chat-with-gpt/commit/95bf0aef6c6aca95b980f6f6e519d429e2158107)
## 2023/03/20/13:03 add typescript tokenizer and better chat trimmer
**Impact on files:**
```
app/craco.config.js
app/package.json
app/src/chat-manager.ts
app/src/components/pages/chat.tsx
app/src/openai.ts
app/src/tiktoken/dist/README.md
app/src/tiktoken/dist/bundler.d.ts
app/src/tiktoken/dist/bundler.js
app/src/tiktoken/dist/init.d.ts
app/src/tiktoken/dist/init.js
app/src/tiktoken/dist/package.json
app/src/tiktoken/dist/tiktoken.d.ts
app/src/tiktoken/dist/tiktoken.js
app/src/tiktoken/dist/tiktoken.node.js
app/src/tiktoken/dist/tiktoken_bg.js
app/src/tiktoken/dist/tiktoken_bg.wasm
app/src/tiktoken/dist/tiktoken_bg.wasm.d.ts
app/src/tiktoken/package.json
app/src/tiktoken/tsconfig.json
app/src/tokenizer.ts
app/src/tokenizer/bpe.ts
app/src/tokenizer/chat-history-trimmer.ts
app/src/tokenizer/cl100k_base.json
app/src/tokenizer/index.ts
```
Check commit: [add typescript tokenizer and better chat trimmer](https://github.com/cogentapps/chat-with-gpt/commit/b6881c69b4f979e70d8069c70998fd01d5e6ceb9)
## 2023/03/19/02:46 fix list numbering
**Impact on files:**
```
app/src/components/markdown.tsx
```
Check commit: [fix list numbering](https://github.com/cogentapps/chat-with-gpt/commit/216ecd5b32da3d0c1ca4746b5d826db36c66ae36)
## 2023/03/19/09:33 improvements, see comments: https://github.com/cogentapps/chat-with-gpt/pull/58
**Impact on files:**
```
app/src/components/input.tsx
app/src/components/settings/user.tsx
app/src/store/api-keys.ts
```
Check commit: [improvements, see comments: https://github.com/cogentapps/chat-with-gpt/pull/58](https://github.com/cogentapps/chat-with-gpt/commit/39e175bef69edbd2e19e4b19ed75f41f97ad3438)
## 2023/03/19/01:46 Merge pull request #53 from Frajder/patch-1
Check commit: [Merge pull request #53 from Frajder/patch-1](https://github.com/cogentapps/chat-with-gpt/commit/583eab23c811dcdada962f9e6e6b775531e57009)
## 2023/03/19/07:22 whisper added
**Impact on files:**
```
app/src/components/input.tsx
app/src/components/message.tsx
app/src/openai.ts
server/src/endpoints/whisper.ts
server/src/index.ts
```
Check commit: [whisper added](https://github.com/cogentapps/chat-with-gpt/commit/e3f4dfef82bf65e3137137d8ee5e3e2b8b1c6919)
## 2023/03/18/16:11 disable helmet
**Impact on files:**
```
server/src/index.ts
```
Check commit: [disable helmet](https://github.com/cogentapps/chat-with-gpt/commit/eeae29da16be0c30f7b7c33a1a5f5d5d3cbd4bf7)
## 2023/03/18/14:06 first framework for using the whisper openai api
**Impact on files:**
```
app/package.json
app/src/components/input.tsx
app/src/components/settings/user.tsx
app/src/store/api-keys.ts
```
Check commit: [first framework for using the whisper openai api](https://github.com/cogentapps/chat-with-gpt/commit/172c5521a525ea3e9e8ecf9e89bab0b7596e2d34)
## 2023/03/18/12:57 removed logging
**Impact on files:**
```
app/src/components/input.tsx
```
Check commit: [removed logging](https://github.com/cogentapps/chat-with-gpt/commit/72cefee277dfb47f819f6fd04aff3d441a388bad)
## 2023/03/18/12:49 added the browser stt api
**Impact on files:**
```
app/package.json
app/src/components/input.tsx
app/src/index.tsx
app/src/speech-recognition-types.d.ts
app/src/store/index.ts
```
Check commit: [added the browser stt api](https://github.com/cogentapps/chat-with-gpt/commit/7e9f67c7b82129f4e4a1eaa307efcc2b18dae93f)
## 2023/03/18/13:26 Update Dockerfile
**Impact on files:**
```
Dockerfile
```
Check commit: [Update Dockerfile](https://github.com/cogentapps/chat-with-gpt/commit/444be8493a7f41f683253671c449f98b28289210)
## 2023/03/18/10:27 remove deploy action
**Impact on files:**
```
.github/workflows/deploy.yml
```
Check commit: [remove deploy action](https://github.com/cogentapps/chat-with-gpt/commit/5a88dfc435184f5fa71e32d74d1a945e7756a107)
## 2023/03/18/10:04 0.2.1
**Impact on files:**
```
app/package.json
server/package.json
```
Check commit: [0.2.1](https://github.com/cogentapps/chat-with-gpt/commit/4190a0d58c7e7c5b9a681be1e95d12c439be3146)
## 2023/03/18/09:56 ga fixes
**Impact on files:**
```
.github/workflows/build.yml
.github/workflows/deploy.yml
```
Check commit: [ga fixes](https://github.com/cogentapps/chat-with-gpt/commit/b7d30dbf4ce6b7d56e8c6ecf012797849eec2ebb)
## 2023/03/18/09:51 beta deploy
**Impact on files:**
```
.github/workflows/deploy.yml
```
Check commit: [beta deploy](https://github.com/cogentapps/chat-with-gpt/commit/5caabedb9eb677a445432e28732e33a05311d0d8)
## 2023/03/18/09:50 new deploy action
**Impact on files:**
```
.github/workflows/deploy.yml
```
Check commit: [new deploy action](https://github.com/cogentapps/chat-with-gpt/commit/8e70e5a7445e1bfd8bbd95bd63e85089a51abc8d)
## 2023/03/18/09:04 meta tags
**Impact on files:**
```
app/public/index.html
```
Check commit: [meta tags](https://github.com/cogentapps/chat-with-gpt/commit/1d0c334f220cc37686d53d6ecc7536d845b46409)
## 2023/03/18/02:05 build sqlite from source
**Impact on files:**
```
Dockerfile
```
Check commit: [build sqlite from source](https://github.com/cogentapps/chat-with-gpt/commit/4eeb7f3478625c52a0221e5ae1325157cdde9a09)
## 2023/03/18/01:53 add update instructions
**Impact on files:**
```
README.md
```
Check commit: [add update instructions](https://github.com/cogentapps/chat-with-gpt/commit/a39ac48549ccc28b6a9527f7d572206993ee3c89)
## 2023/03/18/00:34 add beta branch
**Impact on files:**
```
.github/workflows/publish.yml
```
Check commit: [add beta branch](https://github.com/cogentapps/chat-with-gpt/commit/56c76164a57a9cae6ffc960ed13df1014d5fd8ea)
## 2023/03/18/00:03 add check for non-existant user
**Impact on files:**
```
server/src/database/sqlite.ts
```
Check commit: [add check for non-existant user](https://github.com/cogentapps/chat-with-gpt/commit/00ad70f5b8c814c9220e0a4f0f75561190b9ed26)
## 2023/03/18/00:02 add check for missing user
**Impact on files:**
```
server/src/database/sqlite.ts
```
Check commit: [add check for missing user](https://github.com/cogentapps/chat-with-gpt/commit/0be9133cdcbab50a01955b1a9849fc4ee743bc2b)
## 2023/03/17/22:19 arm support
**Impact on files:**
```
.github/workflows/publish.yml
```
Check commit: [arm support](https://github.com/cogentapps/chat-with-gpt/commit/7b471347bbb7f3b65a45333d815db8b0617810b7)
## 2023/03/17/20:45 add support for deleting chats
**Impact on files:**
```
app/src/backend.ts
app/src/chat-manager.ts
app/src/components/sidebar/index.tsx
app/src/components/sidebar/recent-chats.tsx
app/src/types.ts
server/src/database/index.ts
server/src/database/sqlite.ts
server/src/endpoints/delete-chat.ts
server/src/endpoints/sync.ts
server/src/index.ts
```
Check commit: [add support for deleting chats](https://github.com/cogentapps/chat-with-gpt/commit/1be33f5d0b0cdd8b35e7cab1a5d6bdffb6cec2ba)
## 2023/03/17/19:56 suspense
**Impact on files:**
```
app/src/components/pages/chat.tsx
app/src/tokenizer.ts
```
Check commit: [suspense](https://github.com/cogentapps/chat-with-gpt/commit/6415e3032c3110d079a940c30b7472e04244ffa8)
## 2023/03/17/19:06 only attempt to sync when signed in
**Impact on files:**
```
app/src/backend.ts
```
Check commit: [only attempt to sync when signed in](https://github.com/cogentapps/chat-with-gpt/commit/fe8626cf9d3d223732a2fc6c8d00eac2874e7b3e)
## 2023/03/17/19:05 remove CORS
**Impact on files:**
```
server/src/index.ts
```
Check commit: [remove CORS](https://github.com/cogentapps/chat-with-gpt/commit/a60e261d78a160056c920f99da96995d52b931bb)
## 2023/03/17/19:03 add helmet
**Impact on files:**
```
server/package.json
server/src/index.ts
```
Check commit: [add helmet](https://github.com/cogentapps/chat-with-gpt/commit/b294ac28b1dfdba042702407b16af80066d1aa54)
## 2023/03/17/18:57 more secure password hashing
**Impact on files:**
```
server/package.json
server/src/database/index.ts
server/src/database/sqlite.ts
server/src/passport.ts
```
Check commit: [more secure password hashing](https://github.com/cogentapps/chat-with-gpt/commit/b04e136ee0fdda5b2a04a0b3d7dbc8b657dff7cb)
## 2023/03/17/18:27 use secure default session secret
**Impact on files:**
```
server/src/auth0.ts
server/src/passport.ts
```
Check commit: [use secure default session secret](https://github.com/cogentapps/chat-with-gpt/commit/b0d8d5c20de6c127bd64a5e0c5701869ee1ebcfb)
## 2023/03/17/18:23 sign in button opens create account modal
**Impact on files:**
```
app/src/components/header.tsx
```
Check commit: [sign in button opens create account modal](https://github.com/cogentapps/chat-with-gpt/commit/174feea1b562bce018d6593a11caa292416df2f9)
## 2023/03/17/18:16 add rate limiting
**Impact on files:**
```
server/package.json
server/src/index.ts
```
Check commit: [add rate limiting](https://github.com/cogentapps/chat-with-gpt/commit/d90509c12df676eea28b65fb336a3c7ebb701a33)
## 2023/03/17/03:03 Merge branch 'main' of https://github.com/cogentapps/chat-with-gpt
Check commit: [Merge branch 'main' of https://github.com/cogentapps/chat-with-gpt](https://github.com/cogentapps/chat-with-gpt/commit/bf9ab7d97e31e719baa7d0ae58dc4c48ff0b74a3)
## 2023/03/17/03:03 persist unsubmitted prompts
**Impact on files:**
```
app/src/store/index.ts
```
Check commit: [persist unsubmitted prompts](https://github.com/cogentapps/chat-with-gpt/commit/13eae3da2ef96a415478d75415f9c29c970b3d34)
## 2023/03/16/20:06 preserve language for titles
**Impact on files:**
```
app/src/titles.ts
```
Check commit: [preserve language for titles](https://github.com/cogentapps/chat-with-gpt/commit/bad79bc2b29a082b1fef7f75492915938021e4f0)
## 2023/03/16/20:05 add string descriptions
**Impact on files:**
```
app/package.json
app/public/lang/en-us.json
app/src/components/auth/modals.tsx
app/src/components/header.tsx
app/src/components/input.tsx
app/src/components/markdown.tsx
app/src/components/message.tsx
app/src/components/pages/landing.tsx
app/src/components/settings/index.tsx
app/src/components/settings/options.tsx
app/src/components/settings/speech.tsx
app/src/components/settings/user.tsx
app/src/components/sidebar/index.tsx
app/src/components/sidebar/recent-chats.tsx
app/src/index.tsx
app/src/tts/elevenlabs.tsx
```
Check commit: [add string descriptions](https://github.com/cogentapps/chat-with-gpt/commit/c4a14110ebb347e28a03567f2c0b5e13e6557f1d)
## 2023/03/16/19:06 update strings
**Impact on files:**
```
app/public/lang/en-us.json
app/src/components/auth/modals.tsx
app/src/components/pages/about.tsx
app/src/components/settings/index.tsx
app/src/components/settings/options.tsx
app/src/components/sidebar/index.tsx
app/src/components/sidebar/recent-chats.tsx
app/src/index.tsx
```
Check commit: [update strings](https://github.com/cogentapps/chat-with-gpt/commit/b216cf2900be590cfaf49264bdf7c03ac5a18e66)
## 2023/03/16/09:58 fix svg width
**Impact on files:**
```
app/src/components/markdown.tsx
```
Check commit: [fix svg width](https://github.com/cogentapps/chat-with-gpt/commit/210cca9a44f1322d4844d259c4d6bcd39557817b)
## 2023/03/16/09:48 display svg images in code blocks
**Impact on files:**
```
app/public/index.html
app/public/prose.css
app/src/components/markdown.tsx
```
Check commit: [display svg images in code blocks](https://github.com/cogentapps/chat-with-gpt/commit/869ba3ec1f8b2375af1e8ae17944391dcac8854a)
## 2023/03/15/22:18 add label to gpt-4 messages
**Impact on files:**
```
app/src/components/message.tsx
```
Check commit: [add label to gpt-4 messages](https://github.com/cogentapps/chat-with-gpt/commit/47892360b22bec62e03b71bacfdbe682ddab8ba0)
## 2023/03/15/22:18 save model id on messages
**Impact on files:**
```
app/src/chat-manager.ts
app/src/types.ts
```
Check commit: [save model id on messages](https://github.com/cogentapps/chat-with-gpt/commit/f588b3e484bfb7ba5e6e1c3a62163a38bb400416)
## 2023/03/15/22:14 display model option as dropdown
**Impact on files:**
```
app/public/lang/en-us.json
app/src/components/settings/options.tsx
```
Check commit: [display model option as dropdown](https://github.com/cogentapps/chat-with-gpt/commit/fbc9e1cd1c8a2c9c20a76eed0e1cd9d529932166)
## 2023/03/15/21:50 update package.json
**Impact on files:**
```
app/package.json
```
Check commit: [update package.json](https://github.com/cogentapps/chat-with-gpt/commit/225cb98475bbcfba09e553e4ea067848ff64fddf)
## 2023/03/15/14:49 Merge pull request #33 from openresearch/feature/specify_model
Check commit: [Merge pull request #33 from openresearch/feature/specify_model](https://github.com/cogentapps/chat-with-gpt/commit/49770192ee815a89c376670d737dbacfd496022a)
## 2023/03/15/21:22 link to model names
**Impact on files:**
```
app/src/components/settings/options.tsx
```
Check commit: [link to model names](https://github.com/cogentapps/chat-with-gpt/commit/73e67035b9b5dc27170a1d4e4383fe35430e0b6f)
## 2023/03/15/20:15 update docker instructions
**Impact on files:**
```
README.md
```
Check commit: [update docker instructions](https://github.com/cogentapps/chat-with-gpt/commit/616f9b517dd0fce9fe2946ee370f8b303c3a6aac)
## 2023/03/15/20:13 move folder check
**Impact on files:**
```
server/src/database/sqlite.ts
server/src/index.ts
server/src/object-store/sqlite.ts
```
Check commit: [move folder check](https://github.com/cogentapps/chat-with-gpt/commit/42e297362747cf84c8033213b87b04f556d47428)
## 2023/03/15/21:13 allow to set model name
**Impact on files:**
```
app/src/components/settings/options.tsx
app/src/openai.ts
app/src/parameters.ts
app/src/store/parameters.ts
app/src/titles.ts
app/src/types.ts
```
Check commit: [allow to set model name](https://github.com/cogentapps/chat-with-gpt/commit/1d74cafe2dee062ffcdde892cf846656527f4848)
## 2023/03/15/20:02 update package.json
**Impact on files:**
```
server/package.json
```
Check commit: [update package.json](https://github.com/cogentapps/chat-with-gpt/commit/5f5f48d42ebf1e758faa9f8053e9e5f1c0c94a24)
## 2023/03/15/20:01 Merge branch 'main' of https://github.com/cogentapps/chat-with-gpt
Check commit: [Merge branch 'main' of https://github.com/cogentapps/chat-with-gpt](https://github.com/cogentapps/chat-with-gpt/commit/50ed3ed313e8c778717dd4e02942207a6a1864a8)
## 2023/03/15/20:00 set default port for docker
**Impact on files:**
```
Dockerfile
```
Check commit: [set default port for docker](https://github.com/cogentapps/chat-with-gpt/commit/1cc3d296b018e370f73efad072e215dd6bb4fa36)
## 2023/03/15/12:51 Merge pull request #30 from openresearch/release
Check commit: [Merge pull request #30 from openresearch/release](https://github.com/cogentapps/chat-with-gpt/commit/818485e756d4ed062358432a3846a5efe06b3dfe)
## 2023/03/15/19:47 docker fixes
**Impact on files:**
```
Dockerfile
server/package.json
server/src/index.ts
```
Check commit: [docker fixes](https://github.com/cogentapps/chat-with-gpt/commit/84c5066abd76a2de825ffac54115b9a46a88af15)
## 2023/03/15/20:03 shorter name
**Impact on files:**
```
.github/workflows/publish.yml
```
Check commit: [shorter name](https://github.com/cogentapps/chat-with-gpt/commit/c523ab47bfaf58e9af18862c5d19eb0136212d4f)
## 2023/03/15/20:01 add publish workflow
**Impact on files:**
```
.github/workflows/publish.yml
```
Check commit: [add publish workflow](https://github.com/cogentapps/chat-with-gpt/commit/c48e9187687ac94cfa69c1f6f44d1dcbb182a173)
## 2023/03/14/14:38 Update Dockerfile
**Impact on files:**
```
Dockerfile
```
Check commit: [Update Dockerfile](https://github.com/cogentapps/chat-with-gpt/commit/d1e5a0cda8f66f155664d66f8428362f86024c61)
## 2023/03/14/14:34 Update Dockerfile
**Impact on files:**
```
Dockerfile
```
Check commit: [Update Dockerfile](https://github.com/cogentapps/chat-with-gpt/commit/9944ab190a836fab27c0c0b43ecdbf8c531c43eb)
## 2023/03/14/14:16 Update Dockerfile
**Impact on files:**
```
Dockerfile
```
Check commit: [Update Dockerfile](https://github.com/cogentapps/chat-with-gpt/commit/2f33de691b699d7cbaac17f0a7cfff123058d278)
## 2023/03/14/21:11 github action for docker
**Impact on files:**
```
.github/workflows/build.yml
Dockerfile
server/src/index.ts
```
Check commit: [github action for docker](https://github.com/cogentapps/chat-with-gpt/commit/68e4a5357c23a96fad3e36072ed12c38ab2212d8)
## 2023/03/14/20:25 typescript fixes & github action to build server
**Impact on files:**
```
.github/workflows/build.yml
server/src/database/sqlite.ts
server/src/object-store/sqlite.ts
```
Check commit: [typescript fixes & github action to build server](https://github.com/cogentapps/chat-with-gpt/commit/633630807d74b0f21271fce83012b7b0ebf7b67b)
## 2023/03/14/04:59 Merge pull request #16 from cogentapps/v0.2.0
Check commit: [Merge pull request #16 from cogentapps/v0.2.0](https://github.com/cogentapps/chat-with-gpt/commit/6296d9891103d3f7a1e78272ccc9f56329e4176d)
## 2023/03/14/11:23 fix npm audit warning
**Impact on files:**
```
app/package.json
```
Check commit: [fix npm audit warning](https://github.com/cogentapps/chat-with-gpt/commit/7bc58cb263735d0ccceaa883554ea74f848582d6)
## 2023/03/14/11:12 update readme
**Impact on files:**
```
README.md
```
Check commit: [update readme](https://github.com/cogentapps/chat-with-gpt/commit/4f1314b7eb58542448db119dce23cf72dc26b3f7)
## 2023/03/14/11:09 v0.2.0
**Impact on files:**
```
app/public/index.html
```
Check commit: [v0.2.0](https://github.com/cogentapps/chat-with-gpt/commit/ebdd237e2b32be66aeaefaf6b3f29460988d0ac6)
## 2023/03/14/11:07 restore wasm
**Impact on files:**
```
.gitignore
app/src/tiktoken/dist/README.md
app/src/tiktoken/dist/bundler.d.ts
app/src/tiktoken/dist/bundler.js
app/src/tiktoken/dist/init.d.ts
app/src/tiktoken/dist/init.js
app/src/tiktoken/dist/package.json
app/src/tiktoken/dist/tiktoken.d.ts
app/src/tiktoken/dist/tiktoken.js
app/src/tiktoken/dist/tiktoken.node.js
app/src/tiktoken/dist/tiktoken_bg.js
app/src/tiktoken/dist/tiktoken_bg.wasm
app/src/tiktoken/dist/tiktoken_bg.wasm.d.ts
```
Check commit: [restore wasm](https://github.com/cogentapps/chat-with-gpt/commit/843a703bcd735a81f13accda88192b7930a5c351)
## 2023/03/14/11:05 update readme
**Impact on files:**
```
.gitignore
README.md
```
Check commit: [update readme](https://github.com/cogentapps/chat-with-gpt/commit/5e09a9b4fe3e51262880b30ab49d933fded70939)
## 2023/03/14/11:00 v0.2.0
**Impact on files:**
```
.github/workflows/build.yml
.gitignore
.gitpod.yml
Dockerfile
README.md
app/.gitignore
app/craco.config.js
app/package.json
app/public/favicon.ico
app/public/index.html
app/public/lang/en-us.json
app/public/logo192.png
app/public/logo512.png
app/public/manifest.json
app/public/robots.txt
app/src/backend.ts
app/src/chat-manager.ts
app/src/components/auth/modals.tsx
app/src/components/header.tsx
app/src/components/input.tsx
app/src/components/markdown.tsx
app/src/components/message.tsx
app/src/components/page.tsx
app/src/components/pages/about.tsx
app/src/components/pages/chat.tsx
app/src/components/pages/landing.tsx
app/src/components/settings/index.tsx
app/src/components/settings/option.tsx
app/src/components/settings/options.tsx
app/src/components/settings/speech.tsx
app/src/components/settings/tab.tsx
app/src/components/settings/user.tsx
app/src/components/sidebar/index.tsx
app/src/components/sidebar/recent-chats.tsx
app/src/context.tsx
app/src/idb.ts
app/src/index.scss
app/src/index.tsx
app/src/menus.ts
app/src/message-tree.ts
app/src/openai.ts
app/src/parameters.ts
app/src/react-app-env.d.ts
app/src/setupProxy.js
app/src/spotlight.tsx
app/src/sse.ts
app/src/store/api-keys.ts
app/src/store/index.ts
app/src/store/message.ts
app/src/store/parameters.ts
app/src/store/settings-ui.ts
app/src/store/sidebar.ts
app/src/store/ui.ts
app/src/store/voices.ts
app/src/tiktoken/package.json
app/src/tiktoken/tsconfig.json
app/src/titles.ts
app/src/tokenizer.ts
app/src/tts/defaults.ts
app/src/tts/elevenlabs.tsx
app/src/types.ts
app/src/use-chat.ts
app/src/utils.ts
app/src/values.ts
app/tsconfig.json
craco.config.js
docker-compose.yml
package.json
public/favicon.ico
public/index.html
public/logo192.png
public/logo512.png
public/manifest.json
public/robots.txt
server/package-lock.json
server/package.json
server/src/auth0.ts
server/src/database/index.ts
server/src/database/sqlite.ts
server/src/endpoints/base.ts
server/src/endpoints/completion/basic.ts
server/src/endpoints/completion/streaming.ts
server/src/endpoints/get-share.ts
server/src/endpoints/health.ts
server/src/endpoints/messages.ts
server/src/endpoints/session.ts
server/src/endpoints/share.ts
server/src/endpoints/sync.ts
server/src/endpoints/title.ts
server/src/index.ts
server/src/object-store/index.ts
server/src/object-store/s3.ts
server/src/object-store/sqlite.ts
server/src/passport.ts
server/src/utils.ts
server/tsconfig.json
src/backend.ts
src/chat-manager.ts
src/components/header.tsx
src/components/input.tsx
src/components/markdown.tsx
src/components/message.tsx
src/components/page.tsx
src/components/pages/about.tsx
src/components/pages/chat.tsx
src/components/pages/landing.tsx
src/components/settings/index.tsx
src/components/settings/option.tsx
src/components/settings/options.tsx
src/components/settings/speech.tsx
src/components/settings/tab.tsx
src/components/settings/user.tsx
src/context.tsx
src/idb.ts
src/index.scss
src/index.tsx
src/menus.ts
src/message-tree.ts
src/openai.ts
src/parameters.ts
src/react-app-env.d.ts
src/spotlight.tsx
src/sse.ts
src/store/api-keys.ts
src/store/index.ts
src/store/message.ts
src/store/parameters.ts
src/store/settings-ui.ts
src/store/voices.ts
src/tiktoken/dist/README.md
src/tiktoken/dist/bundler.d.ts
src/tiktoken/dist/bundler.js
src/tiktoken/dist/init.d.ts
src/tiktoken/dist/init.js
src/tiktoken/dist/package.json
src/tiktoken/dist/tiktoken.d.ts
src/tiktoken/dist/tiktoken.js
src/tiktoken/dist/tiktoken.node.js
src/tiktoken/dist/tiktoken_bg.js
src/tiktoken/dist/tiktoken_bg.wasm
src/tiktoken/dist/tiktoken_bg.wasm.d.ts
src/tiktoken/package.json
src/tiktoken/tsconfig.json
src/titles.ts
src/tokenizer.ts
src/tts/defaults.ts
src/tts/elevenlabs.tsx
src/types.ts
src/use-chat.ts
src/utils.ts
src/values.ts
tsconfig.json
```
Check commit: [v0.2.0](https://github.com/cogentapps/chat-with-gpt/commit/645b66b988a50e0e986bbf15aa8328e977b3c00e)
## 2023/03/10/14:06 Merge pull request #11 from cogentapps/redux
Check commit: [Merge pull request #11 from cogentapps/redux](https://github.com/cogentapps/chat-with-gpt/commit/4a5e8c9e16e36d9e712b56e74359965aa19ccc28)
## 2023/03/10/14:04 usecallback deps
**Impact on files:**
```
src/components/header.tsx
```
Check commit: [usecallback deps](https://github.com/cogentapps/chat-with-gpt/commit/e3e435a283cb54a468fceadb1cf2f1e7d581782f)
## 2023/03/10/14:01 eslint
**Impact on files:**
```
src/components/input.tsx
```
Check commit: [eslint](https://github.com/cogentapps/chat-with-gpt/commit/242d01a13a81fc1ece7cf1c9a22aa338cf38659f)
## 2023/03/10/14:00 initial redux work
**Impact on files:**
```
package.json
src/components/header.tsx
src/components/input.tsx
src/components/markdown.tsx
src/components/message.tsx
src/components/page.tsx
src/components/pages/landing.tsx
src/components/settings.tsx
src/components/settings/index.tsx
src/components/settings/option.tsx
src/components/settings/options.tsx
src/components/settings/speech.tsx
src/components/settings/tab.tsx
src/components/settings/user.tsx
src/context.tsx
src/elevenlabs.tsx
src/index.tsx
src/message-tree.ts
src/store/api-keys.ts
src/store/index.ts
src/store/message.ts
src/store/parameters.ts
src/store/settings-ui.ts
src/store/voices.ts
src/tts/defaults.ts
src/tts/elevenlabs.tsx
```
Check commit: [initial redux work](https://github.com/cogentapps/chat-with-gpt/commit/5bfcd9e091ce2c3976f0a6af479a7e1cfc656f7c)
## 2023/03/09/15:57 Update README.md
**Impact on files:**
```
README.md
```
Check commit: [Update README.md](https://github.com/cogentapps/chat-with-gpt/commit/86f6acb62d32c42b6479739a5f9cc7fe6d3fedce)
## 2023/03/09/12:18 eslint fixes
**Impact on files:**
```
src/chat-manager.ts
src/components/header.tsx
src/elevenlabs.tsx
src/use-chat.ts
```
Check commit: [eslint fixes](https://github.com/cogentapps/chat-with-gpt/commit/17b7a68b60eecf5830d6f3f001d0367f0aea33eb)
## 2023/03/09/12:14 fix invalid wasm file
**Impact on files:**
```
src/tiktoken/dist/tiktoken_bg.wasm
```
Check commit: [fix invalid wasm file](https://github.com/cogentapps/chat-with-gpt/commit/f3083f8d2f50da3f4b987018b8d00245e08ae1e6)
## 2023/03/09/12:02 fix invalid wasm file
Check commit: [fix invalid wasm file](https://github.com/cogentapps/chat-with-gpt/commit/5b307c50007c2d6cf48668fe219f582771b68678)
## 2023/03/09/11:50 eslint fixes
**Impact on files:**
```
src/backend.ts
src/chat-manager.ts
src/components/header.tsx
src/components/input.tsx
src/components/pages/chat.tsx
src/components/pages/landing.tsx
src/components/settings.tsx
src/context.tsx
src/elevenlabs.tsx
src/idb.ts
src/spotlight.tsx
src/sse.ts
src/use-chat.ts
```
Check commit: [eslint fixes](https://github.com/cogentapps/chat-with-gpt/commit/7c5ffbbac7f06dfa1d0fd9be1d7fd382883505d6)
## 2023/03/09/11:08 add build action
**Impact on files:**
```
.github/workflows/build.yml
```
Check commit: [add build action](https://github.com/cogentapps/chat-with-gpt/commit/d9aa5aefbe8670c8af9b2cef6f6b04f57f98f200)
## 2023/03/09/02:22 Update README.md
**Impact on files:**
```
README.md
```
Check commit: [Update README.md](https://github.com/cogentapps/chat-with-gpt/commit/b08dcd82b25b738e6fa29ad2bec5c709467e879f)
## 2023/03/09/02:21 Update README.md
**Impact on files:**
```
README.md
```
Check commit: [Update README.md](https://github.com/cogentapps/chat-with-gpt/commit/e9acd997cb9567fe27a23fdfb3379439aabf060e)
## 2023/03/09/01:40 Merge pull request #5 from cogentapps/editing
Check commit: [Merge pull request #5 from cogentapps/editing](https://github.com/cogentapps/chat-with-gpt/commit/28dee69fb97e25070759f5760eff5ecda3037bf9)
## 2023/03/09/01:38 edit and regenerate messages
**Impact on files:**
```
src/chat-manager.ts
src/components/message.tsx
src/context.tsx
```
Check commit: [edit and regenerate messages](https://github.com/cogentapps/chat-with-gpt/commit/aca53b79a0280a85837502ae4c505cbbc75fee5e)
## 2023/03/08/13:56 Merge pull request #4 from cogentapps/2023-03-08
Check commit: [Merge pull request #4 from cogentapps/2023-03-08](https://github.com/cogentapps/chat-with-gpt/commit/63bee572267f4279fd00801c8695ffe6e0f56669)
## 2023/03/08/13:45 add more info about sync
**Impact on files:**
```
src/backend.ts
```
Check commit: [add more info about sync](https://github.com/cogentapps/chat-with-gpt/commit/d82346fec0d3693601d36689313fd9a67687bb5e)
## 2023/03/08/13:45 add install instructions
**Impact on files:**
```
README.md
```
Check commit: [add install instructions](https://github.com/cogentapps/chat-with-gpt/commit/f5c20db0b53ecb6ca2b2ed0799fff561cc0991d3)
## 2023/03/08/13:30 v0.1.1
**Impact on files:**
```
package.json
src/chat-manager.ts
src/components/header.tsx
src/components/input.tsx
src/components/markdown.tsx
src/components/message.tsx
src/components/page.tsx
src/components/pages/about.tsx
src/components/pages/chat.tsx
src/components/pages/landing.tsx
src/components/settings-screen.tsx
src/components/settings.tsx
src/context.tsx
src/index.tsx
src/menus.ts
src/use-chat.ts
```
Check commit: [v0.1.1](https://github.com/cogentapps/chat-with-gpt/commit/27d0314648c5221ff92e098ccd46204ed656f346)
## 2023/03/08/13:17 add tokenizer
**Impact on files:**
```
src/tiktoken/dist/README.md
src/tiktoken/dist/bundler.d.ts
src/tiktoken/dist/bundler.js
src/tiktoken/dist/init.d.ts
src/tiktoken/dist/init.js
src/tiktoken/dist/package.json
src/tiktoken/dist/tiktoken.d.ts
src/tiktoken/dist/tiktoken.js
src/tiktoken/dist/tiktoken.node.js
src/tiktoken/dist/tiktoken_bg.js
src/tiktoken/dist/tiktoken_bg.wasm
src/tiktoken/dist/tiktoken_bg.wasm.d.ts
src/tiktoken/package.json
src/tiktoken/tsconfig.json
src/tokenizer.ts
```
Check commit: [add tokenizer](https://github.com/cogentapps/chat-with-gpt/commit/1796c307d24502453d65a4da1c07c2444b3bdcb2)
## 2023/03/08/10:24 Merge pull request #3 from juangf7/ts-error
Check commit: [Merge pull request #3 from juangf7/ts-error](https://github.com/cogentapps/chat-with-gpt/commit/d259de817cf2f73ed5f8ce200de3a223bf453169)
## 2023/03/08/14:18 fix: :bug: play does not exist on type HTMLElement
**Impact on files:**
```
src/components/settings-screen.tsx
```
Check commit: [fix: :bug: play does not exist on type HTMLElement](https://github.com/cogentapps/chat-with-gpt/commit/2dd120843e1d3e7bbc8bd2c1456d7a185888379c)
## 2023/03/08/14:13 add git ignore file
**Impact on files:**
```
.gitignore
```
Check commit: [add git ignore file](https://github.com/cogentapps/chat-with-gpt/commit/16e5ae4d23fd827a491aeacbc931dac549a137c1)
## 2023/03/07/19:36 Update README.md
**Impact on files:**
```
README.md
```
Check commit: [Update README.md](https://github.com/cogentapps/chat-with-gpt/commit/eb3bcd4f6ebbd9a5c5a161e3a6cbcfffd9884e8b)
## 2023/03/07/18:16 Create LICENSE
**Impact on files:**
```
LICENSE
```
Check commit: [Create LICENSE](https://github.com/cogentapps/chat-with-gpt/commit/0856133c8a507870842be27ab6dbd645faa97a61)
## 2023/03/07/14:51 update README
**Impact on files:**
```
README.md
```
Check commit: [update README](https://github.com/cogentapps/chat-with-gpt/commit/2f560cbc160089f3c12367250ab924c65c372ced)
## 2023/03/07/14:48 add demo video
**Impact on files:**
```
README.md
```
Check commit: [add demo video](https://github.com/cogentapps/chat-with-gpt/commit/b21ad633df10626594c592da78d5349064a890d5)
## 2023/03/07/11:26 fix bugs related to system prompt and titles
**Impact on files:**
```
src/chat-manager.ts
src/components/page.tsx
```
Check commit: [fix bugs related to system prompt and titles](https://github.com/cogentapps/chat-with-gpt/commit/2b99a7299c9c9af84886a907a3dd22b43954ae96)
## 2023/03/06/07:02 Update README.md
**Impact on files:**
```
README.md
```
Check commit: [Update README.md](https://github.com/cogentapps/chat-with-gpt/commit/0f52447203fccbd8afdbf724b2b623c6954d58b7)
## 2023/03/06/06:11 clarify the wording
**Impact on files:**
```
README.md
```
Check commit: [clarify the wording](https://github.com/cogentapps/chat-with-gpt/commit/5b5797a3177b6a2fd5326cf73403739ecb0a768c)
## 2023/03/06/06:09 formatting
**Impact on files:**
```
README.md
```
Check commit: [formatting](https://github.com/cogentapps/chat-with-gpt/commit/a7f4b17aaef03a31f3221dd94271fc6c25816638)
## 2023/03/06/06:07 use more emojis
**Impact on files:**
```
README.md
```
Check commit: [use more emojis](https://github.com/cogentapps/chat-with-gpt/commit/8d7f26f3d4c1970db71b47d84683c8fda62d3de6)
## 2023/03/06/06:03 add readme
**Impact on files:**
```
README.md
```
Check commit: [add readme](https://github.com/cogentapps/chat-with-gpt/commit/59af321b36ef684914ea96460aabe640ef7dabd8)
## 2023/03/06/05:30 v0.1.0
**Impact on files:**
```
craco.config.js
package.json
public/favicon.ico
public/index.html
public/logo192.png
public/logo512.png
public/manifest.json
public/robots.txt
src/backend.ts
src/chat-manager.ts
src/components/header.tsx
src/components/input.tsx
src/components/message.tsx
src/components/page.tsx
src/components/settings-screen.tsx
src/context.tsx
src/elevenlabs.tsx
src/idb.ts
src/index.scss
src/index.tsx
src/message-tree.ts
src/openai.ts
src/parameters.ts
src/react-app-env.d.ts
src/spotlight.tsx
src/sse.ts
src/titles.ts
src/types.ts
src/use-chat.ts
src/utils.ts
src/values.ts
tsconfig.json
```
Check commit: [v0.1.0](https://github.com/cogentapps/chat-with-gpt/commit/1726f5b0f2e2de45d52cd0172086b3df53e18e78)

