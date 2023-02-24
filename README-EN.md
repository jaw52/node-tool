# transform-jsx-for-vite

> This tool is used to assist the traditional React project to VITE support

Used in batches to modify `.js` file suffix names (only modify files containing` jsx` grammar)

- ⚡️`.ts`=>`.tsx`,`.js`=>`.jsx`
- 💡Using `babel` recognition, high accuracy

## Quick Start

Execute the following command under the root directory of the project to be converted

```cmd
npx @jaw52/transform-jsx-for-vite
```

Wait for batch modification of suffix name of '. js'

## Instructions

If the directory name to be scanned is not src, you can use the relative path to specify it

```bash
# 相对路径
Please specify the folder to be scanned ./example/src
Please specify the folder to be scanned example/src
Please specify the folder to be scanned ../example/src
```

##Ignore path

Manually ignore the scanning of some paths. Refer to [fast global] for rules（ https://github.com/mrmlnc/fast-glob#readme )

```bash
# single path
npx @jaw52/transform-jsx-for-vite --ignore **/example/**
# Multiple paths
npx @jaw52/transform-jsx-for-vite --ignore **/.git/** --ignore **/example/**
```