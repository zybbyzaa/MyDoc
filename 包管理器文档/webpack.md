##Webpack文档

###Install

project: `npm install webpack --save-dev`

global: `npm install webpack -g`
###Build

        webpack ./entry.js bundle.js
###ConfigFile

        //web.config.js
        var webpack = require('webpack');
        
        module.exports = {
            target: 'web',
            context: path.resolve(__dirname, '..'),
            entry: {
                app: [
                    
                ]
            }
        };
        