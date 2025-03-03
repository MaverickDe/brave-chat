# Brave Chat

<div align="center">

[![Demo on Cloudflare](https://badgen.net/badge/icon/cloudflare/green?icon=telegram&label=brave-chat)](https://brave-chat-client.pages.dev/landing)
[![Demo on Heroku](https://badgen.net/badge/icon/heroku?icon=telegram&label=brave-chat)](https://brave-chat-demo.herokuapp.com/)
[![Status](https://badgen.net/uptime-robot/status/m780862024-50db2c44c703e5c68d6b1ebb)](https://brave-chat-demo.herokuapp.com/)
[![Tag](https://badgen.net/github/tag/brave-chat/brave-chat)](https://github.com/brave-chat/brave-chat/releases/tag/v0.3.0)
[![Docs](https://badgen.net/badge/icon/docs?icon=wiki&label)](https://docs.brave-chat.wiseai.dev)

</div>

<div align="center">

<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-2-blue.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

</div>

![Brave Chat](./docs/static/images/banner.PNG "Brave Chat")

Brave Chat is a fully featured chat application developed to bring the power back to people. It's designed to be the ultimate open source slack alternative with privacy in mind. It is user-friendly with a clean interface that is easy to navigate.

As well as being feature-rich, Brave Chat is also fully responsive, meaning it will work seamlessly on a wide range of devices. So whether you're chatting on your desktop or your mobile, you'll always have a great experience.

## Supported Features

- Forms validations.

![Email validation.](./docs/static/images/input-validation.png)

![Email validation.](./docs/static/images/password-validation.png)

- Keyboard shortcuts.

![Keyboard shortcuts.](./docs/static/images/keyboard-shortcuts.png)

- Sending and receiving text messages in real time.

![Sending and receiving text messages.](./docs/static/images/snd-rcv-text.gif)

- Sending and receiving images in real time.

![Sending and receiving images.](./docs/static/images/snd-rcv-img.gif)

- Instant notifications when submitting a form.

![Joining a room notification.](./docs/static/images/join-room-notification.png)

![add contact notification.](./docs/static/images/add-contact-notification.png)

- Adding and removing a contact using an email address of a registered user.

![Add contact form.](./docs/static/images/add-contact-form.png)

- Display chat list with unread messages count as a badge and timestamps.

![Custom badges, unread messages count, and timestamps.](./docs/static/images/custom-badges.png)

- Joining and creating rooms given a room name and or description.

![Create room form.](./docs/static/images/create-room.png)

- The ability to click on an avatar in a room to reveal detailed information about a given user.

![Room User Details.](./docs/static/images/room-user-details.png)

- Emojies support.

![Emojies support.](./docs/static/images/emojies.png)

- The ability to leave a room, and delete sent messages.

![Delete messages.](./docs/static/images/delete-messages.png)

![Deleted messages.](./docs/static/images/deleted-messages.png)

- The ability to render HTML tags, links, emails.

![HTML tags being rendered.](./docs/static/images/bold-italic.png)

- The ability to render Markdown text.

![HTML tags being rendered.](./docs/static/images/render-markdown.png)

## 2022 Roadmap

- Enrypt and decrypt text messages on the client side using the signal protocol.
- Add support for voice, videos, files messages.
- Add support for voice and video calls.

## Components

Brave Chat code base is written to be developer-friendly, with code that is both standards-compliant and optimised for performance. It contains a handful list of reusable components. You can take a look at various components in [this section](https://chat-docs.wiseai.dev/folder-structure) of the docs, or expand the following collapsed section.

<details>
<summary><code>tree src</code></summary>

```sh
├── 📂 src
│
│   │
│   ├── 📂 components
│   │
│   │   ├──  📂 AddContact
│   │   │
│   │   │    ├── 📄 index.js
│   │   │    └── 📄 style.css
│   │   │
│   │   ├──  📂 AddRoom
│   │   │
│   │   │    ├── 📄 index.js
│   │   │    └── 📄 style.css
│   │   │
│   │   ├──  📂 AppTextInput
│   │   │ 
│   │   │    └── 📄 index.js
│   │   │
│   │   ├──  📂 ChatContainer
│   │   │
│   │   │    └── 📄 index.js
│   │   │
│   │   ├──  📂 ChatFooter
│   │   │
│   │   │    ├── 📄 index.js
│   │   │    └── 📄 style.css
│   │   │
│   │   ├──  📂 ContentHeader
│   │   │
│   │   │    └── 📄 index.js
│   │   │
│   │   ├──  📂 ContentLoader
│   │   │
│   │   │    └── 📄 index.js
│   │   │
│   │   ├──  📂 Conversation
│   │   │
│   │   │    ├── 📄 index.js
│   │   │    │
│   │   │    ├── 📂 ReceivedMessageCell
│   │   │    │
│   │   │    │   ├── 📄 index.js
│   │   │    │   └── 📄 TypingMessage.js
│   │   │    │
│   │   │    ├── 📂  SentMessageCell
│   │   │    │
│   │   │    │   └── 📄 index.js
│   │   │    │
│   │   │    └── 📄 style.css
│   │   │
│   │   ├──  📂 CustomAlert
│   │   │
│   │   │    ├── 📄 index.js
│   │   │    └── 📄 style.css
│   │   │
│   │   ├──  📂 CustomAvatar
│   │   │
│   │   │    ├── 📄 index.js
│   │   │    └── 📄 style.css
│   │   │
│   │   ├──  📂 CustomCarousel
│   │   │
│   │   │    ├── 📄 index.js
│   │   │    └── 📄 style.css
│   │   │
│   │   ├──  📂 CustomImage
│   │   │
│   │   │    └── 📄 index.js
│   │   │
│   │   ├──  📂 CustomList
│   │   │
│   │   │    ├── 📄 index.js
│   │   │    ├── 📄 ListEmptyResult.js
│   │   │    ├── 📄 ListFooter.js
│   │   │    ├── 📄 ListView.js
│   │   │    └── 📄 style.css
│   │   │
│   │   ├──  📂 CustomPassword
│   │   │
│   │   │    ├── 📄 index.js
│   │   │    └── 📄 style.css
│   │   │
│   │   ├──  📂 CustomTextInput
│   │   │
│   │   │    └── 📄 index.js
│   │   │
│   │   ├──  📂 DropdownMenu
│   │   │
│   │   │    └── 📄 index.js
│   │   │
│   │   ├──  📂 EditInfo
│   │   │
│   │   │    ├── 📄 index.js
│   │   │    └── 📄 style.css
│   │   │
│   │   ├──  📂 EmojiPicker
│   │   │
│   │   │    └── 📄 index.js
│   │   │
│   │   ├──  📂 GridContainer
│   │   │
│   │   │    └── 📄 index.js
│   │   │
│   │   ├──  📂 Helper
│   │   │
│   │   │    └── 📄 index.js
│   │   │
│   │   ├──  📂 MediaViewer
│   │   │
│   │   │    ├── 📄 index.js
│   │   │    └── 📄 style.css
│   │   │
│   │   ├──  📂 PageLoader
│   │   │
│   │   │    ├── 📄 index.js
│   │   │    └── 📄 style.css
│   │   │
│   │   ├──  📂 RoomContentHeader
│   │   │
│   │   │    └── 📄 index.js
│   │   │
│   │   ├──  📂 RoomConversation
│   │   │
│   │   │    ├── 📄 index.js
│   │   │    │
│   │   │    ├── 📂 ReceivedMessageCell
│   │   │    │
│   │   │    │   ├── 📄 index.js
│   │   │    │   └── 📄 TypingMessage.js
│   │   │    │ 
│   │   │    ├── 📂 SentMessageCell
│   │   │    │  
│   │   │    │   └── 📄 index.js
│   │   │    │
│   │   │    └── 📄 style.css
│   │   │
│   │   ├──  📂 Sidebar
│   │   │
│   │   │    ├── 📂 ChatUserCell
│   │   │    │
│   │   │    │   └── 📄 index.js
│   │   │    │
│   │   │    ├── 📂 ChatUserList
│   │   │    │ 
│   │   │    │   └── 📄 index.js
│   │   │    │
│   │   │    ├── 📂 ContactCell
│   │   │    │ 
│   │   │    │   └── 📄 index.js
│   │   │    │ 
│   │   │    ├── 📂 ContactList
│   │   │    │ 
│   │   │    │   └── 📄 index.js
│   │   │    │  
│   │   │    ├── index.js
│   │   │    │ 
│   │   │    ├── 📂 NoRecordFound
│   │   │    │ 
│   │   │    │   ├── 📄 index.js
│   │   │    │   └── 📄 style.css
│   │   │    │ 
│   │   │    ├── 📂 ProfileDetail
│   │   │    │ 
│   │   │    │   └── 📄 index.js
│   │   │    │    
│   │   │    ├── 📂 RoomCell
│   │   │    │ 
│   │   │    │   └── 📄 index.js
│   │   │    ├── 📂 RoomList
│   │   │    │ 
│   │   │    │   └── 📄 index.js
│   │   │    │ 
│   │   │    ├── 📂 SidebarHeader
│   │   │    │  
│   │   │    │   └── 📄 index.js
│   │   │    │  
│   │   │    ├── 📄 style.css
│   │   │    │ 
│   │   │    └── 📂 UserStatus
│   │   │ 
│   │   │        └── 📄 index.js
│   │   │ 
│   │   ├── 📂 SignIn
│   │   │ 
│   │   │   ├── 📄 index.js
│   │   │   └── 📄 style.css
│   │   │ 
│   │   ├── 📂 SignUp
│   │   │ 
│   │   │   └── 📄 index.js
│   │   │ 
│   │   ├── 📄 style.css
```

</details>

### Running locally with NPM

- Fork/Clone the repo:

```sh
git clone git@github.com:wiseaidev/brave-chat.git
```

- Open the newly created directory:

```sh
cd brave-chat
npm install
```

In order to run the project locally or build for production use, you will need to set the following environment variables to connect with the server: 

```sh
REACT_APP_SERVER_URL=http://localhost:8000/api/v1
REACT_APP_SOCKET_URL=ws://localhost:8000/api/v1/ws
```

Now, you can run the client:

```sh
npm start
```

Navigate to [http://localhost:3000](http://localhost:3000) to explore the landing page.

## Running locally with Compose v2

Navigate to [the server repository](https://github.com/brave-chat/brave-chat-server) and follow the instructions listed in [this section](https://github.com/brave-chat/brave-chat-server#running-locally-with-compose-v2) to run both the client and the server in docker containers.

## Deployment

To deploy the client, you will need to set the following environment variables that help the client connect to the server.

```sh
* REACT_APP_SERVER_URL - Your deployed server APIs url.
* REACT_APP_SOCKET_URL - Your deployed server Sockets url.
```

## **Deploy to a Static Hosting Provider**

[![Deploy on Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/brave-chat/brave-chat)

[![Deploy on Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/brave-chat/brave-chat)


## Documentation

You can refer to [the official documentation](https://docs.brave-chat.wiseai.dev) for additional guides, examples, and APIs.

## Contributors

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/wiseaidev"><img src="https://avatars.githubusercontent.com/u/62179149?v=4?s=100" width="100px;" alt="Mahmoud Harmouch"/><br /><sub><b>Mahmoud Harmouch</b></sub></a><br /><a href="#maintenance-wiseaidev" title="Maintenance">🚧</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://www.linkedin.com/in/andrewkykoo/"><img src="https://avatars.githubusercontent.com/u/47183818?v=4?s=100" width="100px;" alt="Andrew Koo "/><br /><sub><b>Andrew Koo </b></sub></a><br /><a href="https://github.com/wiseaidev/brave-chat/commits?author=andrewkykoo" title="Code">💻</a></td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <td align="center" size="13px" colspan="7">
        <img src="https://raw.githubusercontent.com/all-contributors/all-contributors-cli/1b8533af435da9854653492b1327a23a4dbd0a10/assets/logo-small.svg">
          <a href="https://all-contributors.js.org/docs/en/bot/usage">Add your contributions</a>
        </img>
      </td>
    </tr>
  </tfoot>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->