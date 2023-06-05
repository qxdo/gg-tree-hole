# GG Tree Hole

> GG True Hole is a private project, base on [ChatGPT Web](https://github.com/Chanzhaoyu/chatgpt-web)
# Manual Package 
#### Backend

copy `service` folder to your server which has `node` env.


```shell
# Install
pnpm install

# Package
pnpm build

# Run
pnpm prod
```


#### Front

1.Modified the Root Folder `.env` file property `VITE_GLOB_API_URL` point it to your backend server.

2.In your root directory and run this command, and copy the `dist` directory to your server front root directory.
```shell
pnpm build
```


## Thanks
Thanks to this project.

## License
MIT © [qxdo]
