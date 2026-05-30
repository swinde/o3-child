## o3-shop Childtheme

### Shopversion

o3-shop


### general information

This o3-shop child theme can be used for update-safe adjustments to the o3-shop theme.

The folder structure already exists, so you just have to copy the files you want to change from o3-shop into the corresponding folder.
If the child theme is activated, the files it contains are primarily used by the o3 shop.

Don't copy all the files into the child theme, just the ones you want to customize!
The o3-shop takes the files that are not in the child theme from the original o3 theme.


### Installation (short version)

`composer require o3-shop/o3-child`


### Installation (long version)

Create a connection to the server on which your o3-shop eShop is located via SSH client.
Go to your o3-shop project directory, where the composer.json file and the source and vendor folders are located.
Run the following command there: `composer require o3-shop/o3-child`


### Activate child theme

In the admin area under *Extensions → Themes → o3-child_ChildTheme* click the *Activate* button.
Then clear the cache and off you go!

### Development

**Use this method if:** You want to customize the theme or develop new features.

| Requirement | Minimum Version | Notes |
|------------|----------------|-------|
| Node.js | v22.13.0 | [Download](https://nodejs.org/) |
| npm | 10.x | Included with Node.js |
| Gulp CLI | 3.0.0 | [Download](https://gulpjs.com/) |

#### Copy build files for existing theme

```bash
cp -r <DOCUMENT_ROOT>/vendor/o3-shop/o3-theme/build <DOCUMENT_ROOT>/source/Application/views/o3-child
cp -r <DOCUMENT_ROOT>/vendor/o3-shop/o3-theme/package.json <DOCUMENT_ROOT>/source/Application/views/o3-child
```



### License

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.