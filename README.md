<h1 align="center">WhatsApp Clone Using React Native</h1>

<p align="center">
<h5>Description: </h5>
This is an open source clone of whatsapp using the react-native library maintained by facebook, the goal of this project is to build an application exactly like the original application, however using a different technical approach. This project is not for profit and is used only as an object of study on development.

<h5>Stack Project:</h5>
<i>React Native, Redux, Redux Thunk, React Native Router Flux, Firebase</i>
</p>

<hr />


### Running
```shell
git clone git@github.com:filipenatanael/whatsapp-clone-react-native.git
cd whatsapp-clone-react-native
npm install
react-native run-android or react-native run-ios
```

### Firebase Configuration

To set up the firebase, you need to rename **FirebaseSettings.js.example** to **FirebaseSettings.js**. Then, add your apiKey configuration.

```javascript
// whatsapp-clone-react-native/source/resources/FirebaseSettings.js.example

export const config = {
  apiKey: "YOUR-FIREBASE-API-KEY",
  authDomain: "YOUR-FIREBASE-DOMAIN",
  databaseURL: "YOUR-FIREBASE-DATABASE",
  projectId: "YOUR-FIREBASE-PROJECT-ID",
  storageBucket: "YOUR-FIREBASE-STORAGE",
  messagingSenderId: "YOUR-FIREBASE-MASSAGING"
}
```

### Firebase Structure

```json
{
  "messages" : {
    "ZmlsaXBlbmF0YW5hZWwxQGxpdmUuY29t" : {
      "anVsaWFuYUBleGFtcGxlLmNvbQ==" : {
        "-LJHKFv3DtehjTsPivri" : {
          "message" : "Hello, how are you?",
          "type" : "send"
        },
        "-LJHKFv3DtehjTsPivrt" : {
          "message" : "I'm fine and you? :)"
        },
        "-LJHQQy12wRyzRp9q_e8" : {
          "message" : "I'm also fine, Hi.. Let's go out today.",
          "type" : "send"
        },
        "-LJHpYvgmDXFPAl8xznz" : {
          "message" : "Yeah, sure!",
          "type" : "receive"
        },
        "-LJHpdJx0Mc3wTdyWZkD" : {
          "message" : "Where do you wanna go?",
          "type" : "receive"
        },
        "-LJHu8GfIwQKU2T7SZ7-" : {
          "message" : "I want to go to the movies to watch the new Marvel movie",
          "type" : "send"
        },
        "-LJM02ycsXF-4KKCEwzt" : {
          "message" : "I'm leaving home now",
          "type" : "send"
        },
      }
    },
    "anVsaWFuYUBleGFtcGxlLmNvbQ==" : {
      "ZmlsaXBlbmF0YW5hZWwxQGxpdmUuY29t" : {
        "-LJHKFy6pBl_3JnbbJ29" : {
          "message" : "Hello, how are you?",
          "type" : "receive"
        },
        "-LJHpYsPW-X-4VH7_6im" : {
          "message" : "I'm fine and you?",
          "type" : "send"
        },
        "-LJHpdGQoX4B4T5dfQbh" : {
          "message" : "All right?",
          "type" : "send"
        }
      }
    }
  },
  "user_conversations" : {
    "ZmlsaXBlbmF0YW5hZWwxQGxpdmUuY29t" : {
      "anVsaWFuYUBleGFtcGxlLmNvbQ==" : {
        "email" : "sh@example.com",
        "lastMessage" : "I'm leaving home now",
        "name" : "Deep Shah"
      }
    },
	"anVsaWFuYUBleGFtcGxlLmNvbQ==" : {
      "ZmlsaXBlbmF0YW5hZWwxQGxpdmUuY29t" : {
        "email" : "sha@example.com",
        "lastMessage" : "I'm leaving home now",
        "name" : "Bhavya Shah"
      }
    }
  },
  "users" : {
    "ZmlsaXBlbmF0YW5hZWwxQGxpdmUuY29t" : {
      "-LITnhW1yLKAwwvAyPJG" : {
        "name" : "Bhavya Shah"
      }
    },
    "anVsaWFuYUBleGFtcGxlLmNvbQ==": {
      "-L2NfSXjEWlBdxICeLGz" : {
        "name" : "Deep Shah"
      }
    },
	"dG9ueXN0YXJrQGV4ZW1wbGUuY29t==": {
      "-L2NfSXjEWlBdxICeLG2" : {
        "name" : "Mohit"
      }
    }
  },
  "users_of_contacts" : {
    "ZmlsaXBlbmF0YW5hZWwxQGxpdmUuY29t": {
      "-LIYrkTkJ28REbAhD0Xz" : {
        "email" : "sh@example.com",
        "name" : "Deep Shah"
      },
	  "-LIYrkTkJ28REbAhD0X5" : {
        "email" : "shah@exemple.com",
        "name" : "Mohit"
      }
    },
    "anVsaWFuYUBleGFtcGxlLmNvbQ==": {
      "-LJHjLeuvZrC-GTIEL_3" : {
        "email" : "sha@example.com",
        "name" : "Bhavya Shah"
      }
    }
  }
}


```

### References

- [React Native Docs](https://facebook.github.io/react-native/docs/getting-started.html)
- [Firebase](https://firebase.google.com/?hl=pt-br)
- [WhatsApp Messenger](https://play.google.com/store/apps/details?id=com.whatsapp&hl=pt_BR)
- [Redux Thunk](https://github.com/reduxjs/redux-thunk)
- [Community - Android Developers](https://developer.android.com/support)
