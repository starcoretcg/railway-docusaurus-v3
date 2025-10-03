// Minimal, GitBook-style Docusaurus 3 config
// If using TS, this file name is docusaurus.config.ts; for JS it's docusaurus.config.js

const config = {
  title: 'Docs',
  tagline: 'Knowledge base',
  url: 'https://example.com',          // not used at runtime on Railway; just for canonical URLs
  baseUrl: '/',                        // CRITICAL: root path
  onBrokenLinks: 'warn',               // do not fail build
  onBrokenMarkdownLinks: 'warn',
  favicon: 'img/favicon.ico',

  i18n: { defaultLocale: 'en', locales: ['en'] },

  presets: [
    [
      'classic',
      /** @type {import('@docusaurus/preset-classic').Options} */
      ({
        docs: {
          routeBasePath: '/',          // serve docs from root
          sidebarPath: require.resolve('./sidebars.js'),
        },
        blog: false,                   // disable blog entirely
        theme: { customCss: require.resolve('./src/css/custom.css') },
      }),
    ],
  ],

  themeConfig:
    /** @type {import('@docusaurus/preset-classic').ThemeConfig} */
    ({
      navbar: {
        title: 'Docs',
        logo: { alt: 'Logo', src: 'img/logo.svg' },
        items: [
          // Keep this minimal, add search later
        ],
      },
      footer: {
        style: 'dark',
        links: [],
        copyright: `© ${new Date().getFullYear()} Docs`,
      },
      tableOfContents: { minHeadingLevel: 2, maxHeadingLevel: 4 },
    }),
};

module.exports = config;
