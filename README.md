# Vue Storefront - headless PWA for eCommerce
<a href="https://travis-ci.org/DivanteLtd/vue-storefront"><img src="https://travis-ci.org/DivanteLtd/vue-storefront.svg?branch=master" alt="build:passed"></a>
![version](https://img.shields.io/badge/node-v8.x-blue.svg)
![Branch stable](https://img.shields.io/badge/stable%20branch-master-blue.svg)
![Branch Develop](https://img.shields.io/badge/dev%20branch-develop-blue.svg)
<a href="https://join.slack.com/t/vuestorefront/shared_invite/enQtMzA4MTM2NTE5NjM2LTI1M2RmOWIyOTk0MzFlMDU3YzJlYzcyYzNiNjUyZWJiMTZjZjc3MjRlYmE5ZWQ1YWRhNTQyM2ZjN2ZkMzZlNTg">![Branch Develop](https://img.shields.io/badge/community%20chat-slack-FF1493.svg)</a>

Vue Storefront is a standalone PWA storefront for your eCommerce, possible to connect with any eCommerce backend (eg. Magento, <a href="https://github.com/DivanteLtd/pimcore2vuestorefront">Pimcore</a>,  Prestashop or Shopware) through the API.

Vue Storefront is and always will be in the open source. Anyone can use and support the project, we want it to be a tool for the improvement of the shopping experience.
The project is in the **production ready** phase.

**Important note to developers:** From 1.0RC we started using [develop](https://github.com/DivanteLtd/vue-storefront/tree/develop) branch for nightly builds (contains all new features) and [master](https://github.com/DivanteLtd/vue-storefront/tree/master) branch for stable. Please make sure you're working on right branch. Please take alook at [Contributing guidelines](https://github.com/DivanteLtd/vue-storefront/blob/master/CONTRIBUTING.md).

**We are looking for Contributors and Designer willing to help us in the solution development.**

See the ideas behind Vue Storefront [here](https://www.slideshare.net/FilipRakowski/vue-storefront-basics)

**Read [contribution rules](https://github.com/DivanteLtd/vue-storefront/blob/master/CONTRIBUTING.md) before making any pull request. Pull request that don't meet this requirements will not be merged**
## See it in action

<table>
  <tbody>
    <tr>
      <td align="center" valign="middle">
        <a href="https://demo.storefrontcloud.io">
          <img
            src="https://github.com/DivanteLtd/vue-storefront/blob/master/doc/media/demo-b2c.png?raw=true"
            alt="B2C Theme demo"
            style="width: 100px;">
        </a>
      </td>
      <td align="left" valign="top">
        Try out our open demo and if you like it <strong>first give us some star on Github ★</strong> and then contact us on <a href="https://slack.vuestorefront.io">Slack</a> or via contributors@vuestorefront.io. <br /><br /> This demo site is connected to <a href="http://demo-magento2.vuestorefront.io">Magento 2.2</a> with shopping carts and users synchronization so You can make an order (which unofrtunatelly won't be shipped ;P). <br /><br />If You like to see Magento 1 integration demo please <a href="https://vuestorefront.io">do contact us</a>.
      </td>
</tr>
  </tbody>
</table>

 ## Video demo
 [![See how it works!](doc/media/vs-video.png)](https://www.youtube.com/watch?v=L4K-mq9JoaQ)

 ## Technical Webcast #1 - demo and the architecture
 [![Demo and the architecture of Vue Storefront](doc/media/video-webcast-1.png)](https://www.youtube.com/watch?v=sRSmEP4jva0&feature=youtu.be)

- [Read on how to integrate it with Magento2](https://medium.com/@piotrkarwatka/vue-storefront-how-to-install-and-integrate-with-magento2-227767dd65b2), [Read how to create Vue Storefront theme](https://medium.com/@frakowski/developing-themes-in-vue-storefront-backend-agnostic-ecommerce-pwa-frontend-part-1-72ea3c939593),
- [Read the interviews with authors of first production deployments](https://medium.com/@piotrkarwatka/vue-storefront-on-production-interview-with-gogetgold-com-developers-71e4b48ef996)


## Is it production ready?

Yes! There are more than 10 implementations happening right now and many live shops (check [awesome Vue Storefront list](https://github.com/frqnck/awesome-vue-storefront)).

## Join the community on Slack
If you have any questions or ideas feel free to join our slack: https://vuestorefront.slack.com via [invitation link](https://join.slack.com/t/vuestorefront/shared_invite/enQtMzA4MTM2NTE5NjM2LTI1M2RmOWIyOTk0MzFlMDU3YzJlYzcyYzNiNjUyZWJiMTZjZjc3MjRlYmE5ZWQ1YWRhNTQyM2ZjN2ZkMzZlNTg)

## Roadmap
We are planning 1-2 milestones ahead. Our milestones are based on requirements from community, partners and production implementations.
[See the roadmap](https://github.com/DivanteLtd/vue-storefront/milestones).
[Check the feature list of 1.0](https://github.com/DivanteLtd/vue-storefront/blob/master/doc/Feature%20list.md).

## Documentation + table of contents
The documentation is always THE HARDEST PART of each open source project! But we're trying hard. Please find out what we've already managed to prepare under /doc folder: https://github.com/DivanteLtd/vue-storefront/tree/master/doc. There is also new, updated `/docs` folder with original documentation migrated to VuePress (Work in Progress).

**Please try out our NEW DOCS:** [available on Github Pages](https://divanteltd.github.io/vue-storefront/). Please note that new docs are still Work In Progress and will be successfully updated.

You can find some tutorials and explainations on our [YouTube channel](https://www.youtube.com/channel/UCkm1F3Cglty3CE1QwKQUhhg)

### Installation
* [Installing on Linux/MacOS](https://github.com/DivanteLtd/vue-storefront/blob/master/doc/Installing%20on%20Linux%20and%20MacOS.md)
* [Installing on Windows](https://github.com/DivanteLtd/vue-storefront/blob/master/doc/Installing%20on%20Windows.md)
* [How to install and integrate with Magento2](https://medium.com/@piotrkarwatka/vue-storefront-how-to-install-and-integrate-with-magento2-227767dd65b2)
* [Production setup](https://github.com/DivanteLtd/vue-storefront/blob/master/doc/Production%20setup%20(WIP).md)
* [Configuration file explained](https://github.com/DivanteLtd/vue-storefront/blob/develop/doc/Config%20docs.md)

### Basics
* [Project structure](https://github.com/DivanteLtd/vue-storefront/blob/master/doc/Project%20structure.md) - good for introduction
* [Contribution and issue reporting guideness](https://github.com/DivanteLtd/vue-storefront/blob/master/CONTRIBUTING.md)
* [FAQ / Receipes](https://github.com/DivanteLtd/vue-storefront/blob/master/doc/FAQ%20and%20Receipes.md)
* [Feature list](https://github.com/DivanteLtd/vue-storefront/blob/master/doc/Feature%20list.md)
* [Vue Storefront modules](https://github.com/DivanteLtd/vue-storefront/blob/master/doc/api-modules/about-modules.md)
* [TypeScript Action Plan](https://github.com/DivanteLtd/vue-storefront/blob/master/doc/TypeScript%20Action%20Plan.md)
* [GraphQL Action Plan](https://github.com/DivanteLtd/vue-storefront/blob/develop/doc/GraphQL%20Action%20Plan.md)
* [Entity Types](https://github.com/DivanteLtd/vue-storefront/blob/develop/doc/Entity%20Types.md)
* [SSR Cache](https://github.com/DivanteLtd/vue-storefront/blob/develop/doc/SSR%20Cache.md)

### Vue Storefront core and themes
* [Working with themes](https://github.com/DivanteLtd/vue-storefront/blob/master/doc/themes/Working%20with%20themes.md)
* [Layouts and advanced output operations](https://github.com/DivanteLtd/vue-storefront/blob/develop/doc/Layouts%20and%20advanced%20output%20operations.md)
* [Working with Vue Storefront core components](https://github.com/DivanteLtd/vue-storefront/blob/master/doc/components/Working%20with%20components.md)
* [Working with UI Store (interface state)](https://github.com/DivanteLtd/vue-storefront/blob/master/doc/Working%20with%20UI%20Store%20(interface%20state).md)
* [Working with translations](https://github.com/DivanteLtd/vue-storefront/blob/master/doc/i18n/Working%20with%20translations.md)
* [Working with Service Workers](https://github.com/DivanteLtd/vue-storefront/blob/master/doc/Working%20with%20service-worker.md)
* [Working with Webpack](https://github.com/DivanteLtd/vue-storefront/blob/master/doc/Working%20with%20webpack.md)
* [Working with plugins](https://github.com/DivanteLtd/vue-storefront/blob/master/doc/Working%20with%20plugins.md)
* [[TEMPORARY] Core components and pages docs](https://github.com/DivanteLtd/vue-storefront/blob/master/doc/components/%5Btemporary%5D%20core%20components%20API.md)

Tutorial series on creating themes for Vue Storefront:
* [Creating themes in Vue Storefront (part 1 — understanding Vue Storefront core)](https://medium.com/@frakowski/developing-themes-in-vue-storefront-backend-agnostic-ecommerce-pwa-frontend-part-1-72ea3c939593)

### Data in Vue Storefront
* [Working with data](https://github.com/DivanteLtd/vue-storefront/blob/master/doc/Working%20with%20data.md)
* [Working with Vuex](https://github.com/DivanteLtd/vue-storefront/blob/master/doc/data/Working%20with%20Vuex.md)
* [ElasticSearch data formats](https://github.com/DivanteLtd/vue-storefront/blob/master/doc/ElasticSearch%20data%20formats.md)
* [Data Migrations for ElasticSearch](https://github.com/DivanteLtd/vue-storefront-api/blob/master/doc/1.%20Data%20schema%20and%20migrations.md)
* [ElasticSearch Queries](https://github.com/DivanteLtd/vue-storefront/blob/master/doc/data/ElasticSearch%20Queries.md)
* [Database tool](https://github.com/DivanteLtd/vue-storefront/blob/master/doc/Database%20tool.md)
* [Adding Custom Entity Types](https://github.com/DivanteLtd/vue-storefront/blob/develop/doc/Entity%20Types.md)

### Working with Vue Storefront Extensions
* [Working with extensions](https://github.com/DivanteLtd/vue-storefront/blob/master/doc/extensions/Working%20with%20extensions.md)
* [Adding custom Server API methods](https://github.com/DivanteLtd/vue-storefront/blob/master/doc/Extending%20vue-storefront-api.md)
* [Extending UI from extensions](https://github.com/DivanteLtd/vue-storefront/blob/master/doc/components/Extending%20UI%20from%20extensions.md)
* [Adding Express routes and middlewares](https://github.com/DivanteLtd/vue-storefront/blob/master/doc/Extending%20Express.js%20server%20side%20routes.md)

### Integrations
* [Vue Storefront + Magento](https://github.com/DivanteLtd/mage2vuestorefront)
* [Vue Storefront + Magento 1.9](https://github.com/DivanteLtd/magento1-vsbridge)
* [Vue Storefront + with Magento checkout](https://github.com/DivanteLtd/magento2-external-checkout)
* [Vue Storefront + Pimcore](https://github.com/DivanteLtd/pimcore2vuestorefront)
* [Magento2 Product Reviews](https://github.com/DivanteLtd/vue-storefront/blob/develop/doc/Reviews.md)
* [PayPal Payments integration](https://github.com/DivanteLtd/vue-storefront/blob/develop/doc/PayPal%20payments%20support.md)
* [Direct prices sync with Magento](https://github.com/DivanteLtd/vue-storefront/blob/master/doc/Direct%20Prices.md)
* [Tier prices sync with Magento](https://github.com/DivanteLtd/vue-storefront/blob/master/doc/Tier%20prices.md)
* [Shopping carts, totals and orders sync](https://github.com/DivanteLtd/vue-storefront/blob/master/doc/Totals%2C%20cart%2C%20orders%20sync%20with%20Magento.md)
* [Vue Storefront 3rd party platforms integration boilerplate](https://github.com/DivanteLtd/vue-storefront-integration-boilerplate) - this is the API You should implement to integrate 3rd party platform
* [Magento2 MultiStore support](https://github.com/DivanteLtd/vue-storefront/blob/master/doc/Multistore%20setup.md)

### Core API Modules docs (experimental feature, not safe to use right now)
* [Cart Module](https://github.com/DivanteLtd/vue-storefront/blob/master/doc/api-modules/cart.md)
### 'Default theme' contribution rules
* [Working with stylesheets (CSS)](https://github.com/DivanteLtd/vue-storefront/blob/master/doc/themes/default/Working%20with%20stylesheets.md)

## Awesome projects related to Vue Storefront
Check [Vue Storefront Awesome](https://github.com/frqnck/awesome-vue-storefront)
## The business challenges
Vue Storefront was created to solve a set of key business challenges from the world of shopping experience. Our goal for the application is to provide the solution with:
* The ultrafast front-end for the store - with the PWA approach we can now render the catalog of products within milliseconds;
* The endurance for traffic overloads on the store;
* The off-line shopping capabilities;
* The smooth shopping experience close to the user experience from the native mobile applications;
* The all-in-one front-end for desktop and mobile screens with no necessity for maintaining 3 or more applications for different touchpoints (web browser, Android, iOS etc.).
* Rapid development without architecture limitations.

## The technology
Vue Storefront was built as an all-in-one front-end for eCommerce. For providing the best performance we decided to use Vue.js as a front-end library, Node.js + Express (and maybe GraphQL support) as a server-API, Elastic Search as a database of products and full PWA/off-line support.
Here you can read more about the proof of concept for [Vue Storefront connected with Magento2](https://www.linkedin.com/pulse/magento2-nosql-database-pwa-support-piotr-karwatka).

Besides a big improvement for the shopping experience, we also want to create a great code base for every developer who needs to work on a front-end application for the eCommerce.

## The architecture
![Architecture diagram](doc/media/arch.png)

## The design
The application is prepared to be fully customized in design through theming system.
With the current version we work on raw, basic template of typical eCommerce for a fashion industry.
In the project we used [Material Icons](https://github.com/google/material-design-icons).

<img width="880" alt="Vue Storefront - Annimations in sidebar menu" src="https://user-images.githubusercontent.com/18116406/33559404-ed674bcc-d90c-11e7-864a-91e42d1c92cd.gif">

<img width="880" alt="Vue Storefront - Annimations in featured products box" src="https://user-images.githubusercontent.com/18116406/33559277-920deb00-d90c-11e7-95e6-ffd55a36a5c6.gif">

Here you can read more about the process of [designing PWA for eCommerce](https://www.linkedin.com/pulse/designing-pwa-ecommerce-karl-bzik/).

The design is available in open source in the Figma file format under the URL https://www.figma.com/file/VKyqbHFI55TKIKcQlFLiVpVF/Vue-Storefront-Open-Source.

## Other platforms
Vue Storefront is platform agnostic which means it can be connected to virtually any CMS. Please take a look at [Pimcore bridge](https://github.com/DivanteLtd/pimcore2vuestorefront) to give you an idea on how other platforms can be connected. Any support for integrating Prestashop, Shopify ... - much appreciated.

## The license
Vue Storefront source code is completely free and released under the [MIT License](https://github.com/DivanteLtd/vue-storefront/blob/master/LICENSE).

## Contributing
If you like the idea behind Vue Storefront and want to become a contributor - do not hesitate and check our [list of the active issues](https://github.com/DivanteLtd/vue-storefront/issues) or contact us directly via contributors@vuestorefront.io.

If you have discovered a 🐜 or have a feature suggestion, feel free to create an issue on Github.

## Workshops
If you like our project and would like to learn more on how to create Progressive Web Apps you can ask us for dedicated workshop at your office! Conducted by Vue Storefront core contributors! All the profits are used for supporting Vue Storefront development. [Learn more](https://products.divante.co/vuestorefront/)

## Support us!
**Vue Storefront is and always will be Open Source, released under MIT Licence.**

Most of the core team members, VS contributors and contributors in the ecosystem do this open source work in their free time. If you use Vue Storefront for a serious task, and you'd like us to invest more time on it, you can donate the project! You can support us in various ways:
- **Contribute** - this is how the Core Team is supporting the project!
- **Evangelize** - tweet about us, take some speaking slot at tech conference etc.
- **Sponsor** - if you're doing serious business on VS maybe You would like to donate the project and put your logo in here?

This is how we will use the donations:

- Allow the core team to work on VS
- Thank contributors if they invested a large amount of time in contributing
- Support projects in the ecosystem that are of great value for users
- Infrastructure cost
- Fees for money handling

**If you would like to support us please just let us know: contributors@vuestorefront.io**

## Partners
Vue Storefront is a Community effort brought to You by our great Core Team and supported by the following companies.

<table>
  <tbody>
    <tr>
      <td align="center" valign="middle">
        <a href="https://divante.co/">
          <img
            src="https://divante.co/about us/LOGO.png"
            alt="Divante"
            width="120"
          >
        </a>
      </td>
      <td align="center" valign="middle">
        <a href="https://snow.dog">
          <img
            src="https://snow.dog/wp-content/themes/snowwptheme/assets/images/logo.png"
            alt="Snow.dog"
            height="50"
          >
        </a>
      </td>
      <td align="center" valign="middle">
        <a href="https://www.wagento.com">
          <img
            src="https://www.wagento.com/media/wysiwyg/logo-color-tagline_4x.png"
            alt="Wagento"
            height="50"
          >
        </a>
      </td>
      <td align="center" valign="middle">
        <a href="http://www.summasolutions.net">
          <img
            src="http://www.summasolutions.net/sites/all/themes/summa2015/images/logo-tablet.jpg"
            alt="Summa Solutions"
            height="50"
          >
        </a>
      </td>
      <td align="center" valign="middle">
        <a href="http://www.acidgreen.com.au/">
          <img
            src="https://cdn.dribbble.com/users/469310/screenshots/3865916/acidgreen_logo.jpg"
            alt="Acid Green"
            height="50"
          >
        </a>
      </td>
    </tr>
    <tr>
      <td align="center" valign="middle">
        <a href="http://macopedia.com/pl">
          <img
            src="doc/media/logo_light-kopia.png"
            alt="Macopedia"
            height="50"
          >
        </a>
      </td>
      <td align="center" valign="middle">
        <a href="http://www.develodesign.co.uk/">
          <img
            src="doc/media/develo_logo.png"
            alt="Macopedia"
            height="50"
          >
        </a>
      </td>
      <td align="center" valign="middle">
        <a href="https://magenest.com/">
          <img
            src="https://user-images.githubusercontent.com/18116406/37145068-3326bdf8-22c0-11e8-9bc1-0b9b2377129f.png"
            alt="Magenest"
            height="50"
          >
        </a>
      </td>
      <td align="center" valign="middle">
        <a href="https://www.ecommbits.com/en/">
          <img
            src="https://user-images.githubusercontent.com/18116406/37145348-ea9c8ba2-22c0-11e8-9a91-d1a1da9af782.png"
            alt="ECOMMBITS"
            height="50"
          >
        </a>
      </td>
      <td align="center" valign="middle">
        <a href="https://www.optiweb.com/">
          <img
            src="https://user-images.githubusercontent.com/18116406/37145626-9d48077c-22c1-11e8-82fd-dda1268d05e9.png"
            alt="Optiweb"
            height="50"
          >
        </a>
      </td>
    </tr>
    <tr>
      <td align="center" valign="middle">
        <a href="https://www.bitbull.it/">
          <img
            src="https://user-images.githubusercontent.com/18116406/38270766-b0bc4fc0-3784-11e8-9463-99d88950ca9a.png"
            alt="Bitbull"
            height="50"
          >
        </a>
      </td>
       <td align="center" valign="middle">
        <a href="https://vendic.nl/">
          <img
            src="https://divante.co/partners/Vue-Storefront/vendic-rood.png"
            alt="Vendic"
            height="50"
          >
        </a>
      </td>
      <td align="center" valign="middle">
        <a href="https://www.getnoticed.nl/">
          <img
            src="https://user-images.githubusercontent.com/18116406/38860463-87a9fff4-4230-11e8-8017-e5ffb73e77f9.png"
            alt="Get.Noticed"
            height="50"
          >
        </a>
      </td>
      <td align="center" valign="middle">
        <a href="http://novatize.com/">
          <img
            src="https://user-images.githubusercontent.com/18116406/39051246-62220fae-44a8-11e8-92d3-3bbe02644313.png"
            alt="Novatize"
            height="50"
          >
        </a>
      </td>
      <td align="center" valign="middle">
        <a href="https://www.imaginationmedia.com/">
          <img
            src="https://user-images.githubusercontent.com/18116406/39051477-0c46c1aa-44a9-11e8-8f53-0adabe3e66a4.png"
            alt="Imagination Media"
            height="50"
          >
        </a>
      </td>
    </tr>
    <tr>
        <td align="center" valign="middle">
        <a href="https://magedirect.co/">
          <img
            src="https://user-images.githubusercontent.com/18116406/38415925-4a31e358-3993-11e8-9bee-b2b9af95d305.png"
            alt="MageDirect"
            height="50"
          >
        </a>
      </td>
      <td align="center" valign="middle">
        <a href="https://www.edmondscommerce.co.uk/">
          <img
            src="https://divante.co/partners/Vue-Storefront/edmonds-ecommerce.png"
            alt="Edmonds Commerce"
            height="50"
          >
        </a>
      </td>
      <td align="center" valign="middle">
        <a href="https://www.kt-team.ru/">
          <img
            src="https://divante.co/partners/Vue-Storefront/kt.team.png"
            alt="KT Team"
            height="50"
          >
        </a>
      </td>
      <td align="center" valign="middle">
        <a href="https://magebit.com/">
          <img
            src="https://divante.co/partners/Vue-Storefront/Magebit_150px.png"
            alt="MageBit"
            height="50"
          >
        </a>
      </td>
     <td align="center" valign="middle">
        <a href="https://upsidelab.io/">
          <img
            src="https://divante.co/partners/Vue-Storefront/upside-logo@4x.png"
            alt="UpsideLab"
            height="50"
          >
        </a>
       </td>
    </tr>
     <tr>
       <td align="center" valign="middle">
        <a href="http://meigee.team/">
          <img
            src="https://divante.co/partners/Vue-Storefront/meigee.png"
            alt="Meigee"
            height="50"
          >
        </a>
      </td>
         <td align="center" valign="middle">
        <a href="https://webvisum.de/">
          <img
            src="https://divante.co/partners/Vue-Storefront/Webvisium-Logo.png"
            alt="WebVisum"
            height="50"
          >
        </a>
      </td>
      <td align="center" valign="middle">
        <a href="https://www.phoenix-media.eu/">
          <img
            src="https://divante.co/partners/Vue-Storefront/PHOENIX_MEDIA_Logo_transparent.png"
            alt="Phoenix Media"
            height="50"
          >
        </a>
      </td>
  <td align="center" valign="middle">
        <a href="https://viaict.com/">
          <img
            src="https://www.viaict.com/img/viaict_flat_design_300.png"
            alt="Viaict"
            height="50"
          >
        </a>
      </td>
        <td align="center" valign="middle">
        <a href="https://bemeir.com/vue-storefront">
          <img
            src="https://divante.co/partners/Vue-Storefront/bemeir.png"
            alt="Bemeir"
            height="40"
          >
        </a>
      </td>
    </tr>
     <tr>
       <td align="center" valign="middle">
        <a href="http://copex.io/">
          <img
            src="https://divante.co/partners/Vue-Storefront/copex-io-logo.png"
            alt="Copex.io"
            height="50"
          >
        </a>
      </td>
         <td align="center" valign="middle">
        <a href="https://www.badger.blue/">
          <img
            src="https://divante.co/partners/Vue-Storefront/BlueBadger-Logo.png"
            alt="Badger Blue"
            height="50"
          >
        </a>
      </td>
        <td align="center" valign="middle">
        <a href="">
          <img
            src=""
            alt=""
            height="50"
          >
        </a>
      </td>
    <td align="center" valign="middle">
        <a href="">
          <img
            src=""
            alt=""
            height="50"
          >
        </a>
      </td>
         <td align="center" valign="middle">
        <a href="">
          <img
            src=""
            alt=""
            height="50"
          >
        </a>
      </td>
    </tr>
  </tbody>
</table>

Partners are encouraged to support the project by various ways - mostly by contributing the source code, marketing activities, evangelizing and of course - implementing the production projects. We do support our partners by dedicated contact channels, workshops and by sharing the leads from merchants interested in implementations.

If you like to become our Partner just let us know via contributors@vuestorefront.io.

## The screenshots

<img width="880" alt="Vue Storefront - Annimations in the sidebar cart" src="https://user-images.githubusercontent.com/18116406/33559769-2840fb70-d90e-11e7-8f2b-298f35d1b412.gif">

<img width="880" alt="Vue Storefront - Annimations on producy card" src="https://user-images.githubusercontent.com/18116406/33560504-3105dac6-d910-11e7-847d-70ef8e944321.gif">

