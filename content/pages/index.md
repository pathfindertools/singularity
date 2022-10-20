---
draft: true
blocks:
  - style:
      alignment: 'flex-row-reverse items-center items-center-vertical '
      padding: pt-48 pb-20 pr-20 pl-20
      featureImage: wpx-300 hpx- mx-auto
      featureContent: w-1/2 min-h-0 text-left
      labelStyles: text-white font-2 text-xl mb-0 font-bold
      headlineStyles: text-white font-1 text-6xl mb-1.5 font-bold
      subheadStyles: text-white font-1 text-xl mb-7 font-bold
      textStyles: 'text-white font-1 text-lg mb-11 '
      contentOrder: labelHeadingsContent
    background:
      fillStyles: from-primary to-accent2 bg-gradient-to-br opacity-100
    image:
      src: >-
        https://res.cloudinary.com/protocolai/image/upload/v1666227311/ICON_COLOR_djhirl.svg
      alt: Singularity logo
    label: ''
    headline: Singularity
    subhead: An end-to-end solution for data onboarding to Filecoin.
    body: >
      Facilitating petabyte-scale data ingestion for storage clients and
      providers.
    buttons:
      - label: Get started
        link: 'https://github.com/tech-greedy/singularity'
        type: primary
      - label: Learn more
        link: 'https://github.com/tech-greedy/singularity/wiki/Design'
        type: secondary
    _template: feature
  - style:
      textAlignment: text-left
      minHeight: min-h-0
      padding: pt-20 pb-20 pr-20 pl-20
      contentWidth: w-full
      columns: '2'
      labelStyles: text-black font-1 text-xl mb-0 font-bold
      headlineStyles: text-white undefined text-5xl mb-11 font-bold
      subheadStyles: text-black undefined text-3xl mb-0 font-bold
      textStyles: text-black undefined text-lg mb-0 font-bold
      contentOrder: labelHeadingsContent
    cardStyle:
      fillStyles: ' opacity-100'
      padding: pt-4 pb-4 pr-5 pl-7
      borderStyles: border-primary border-3
      labelStyles: 'text-white undefined text-sm mb-0 '
      headlineStyles: text-white font-1 text-xl mb-2 font-bold
      subheadStyles: 'text-black undefined text-lg mb-0 '
      textStyles: 'text-white undefined text-lg mb-0 '
      buttonType: primary
    background:
      fillStyles: from-primary to-accent2 bg-gradient-to-tr opacity-100
    label: ''
    headline: Features
    subhead: ''
    body: ''
    items:
      - headline: Simple data processing
        subhead: ''
        text: >
          Singularity automates data preparation by automatically chunking your
          data and generating CAR files.
        link: ''
        buttonLabel: ''
      - headline: Configurable and modular
        subhead: ''
        text: >
          Pick-and-choose the components you want. Process local data or point
          to a public S3 bucket.
      - headline: Robust deal execution
        subhead: ''
        text: >
          Customize the deal execution strategy: deal with your preferred
          storage providers with a schedule that works.
      - headline: Indexing and retrieval
        subhead: ''
        text: >
          Data is automatically indexed on IPFS. Retrievals are done with a
          simple command.
    navigationLabel: Features
    _template: textCards
  - style:
      textAlignment: text-center
      minHeight: min-h-0
      padding: pt-20 pb-20 pr-10 pl-10
      width: narrow
      labelStyles: 'text-black font-1 text-sm mb-0 '
      headlineStyles: 'text-black font-1 text-5xl mb-0 '
      subheadStyles: 'text-black font-1 text-3xl mb-0 '
      textStyles: 'text-white font-1 undefined mb-0 '
      contentOrder: labelHeadingsContent
    background:
      fillStyles: from-primary to-accent2 bg-gradient-to-br opacity-100
      position: object-right
      ornaments:
        - src: >-
            https://res.cloudinary.com/protocolai/image/upload/v1666227018/data-onboarding-assets-DO-Primary-White_phrtte.png
          alignment: top
          width: '150'
          xOffset: ''
          yOffset: '10'
    label: ''
    headline: ''
    subhead: ''
    body: "Singularity is an open-source tool designed by [@Xinan Xu](https://github.com/xinaxu) and [@Fei Yan](https://github.com/kernelogic) and maintained by the Data Onboarding team at Protocol Labs. Our goal is to develop tools that help data owners and storage providers ingest massive amounts of data to the Filecoin network.\n\nIt is a easy-to-use [NPM package](https://www.npmjs.com/package/@techgreedy/singularity) that works with [Lotus](https://lotus.filecoin.io/) and [Boost](https://boost.filecoin.io/) to tie together every step of data onboarding.\_\n"
    _template: banner
  - style:
      textAlignment: text-left
      minHeight: min-h-0
      padding: pt-20 pb-20 pr-20 pl-20
      contentWidth: w-full
      columns: '1'
      labelStyles: 'text-black font-1 text-sm mb-0 '
      headlineStyles: text-white font-1 text-5xl mb-11 font-bold
      subheadStyles: 'text-black font-1 text-3xl mb-0 '
      textStyles: 'text-black font-1 text-lg mb-0 '
      contentOrder: labelHeadingsContent
    cardStyle:
      fillStyles: ' opacity-100'
      padding: pt-4 pb-4 pr-4 pl-4
      borderStyles: border-primary border-3
      labelStyles: 'text-black font-1 text-sm mb-0 '
      headlineStyles: text-white font-1 text-xl mb-2 font-bold
      subheadStyles: 'text-black font-1 undefined mb-0 '
      textStyles: 'text-white font-1 text-lg mb-0 '
      buttonType: primary
    background:
      fillStyles: from-accent2 to-primary bg-gradient-to-bl opacity-100
    label: ''
    headline: How it works
    subhead: ''
    body: ''
    items:
      - headline: 1. Prepare the data
        subhead: ''
        text: >
          The data preparation module will scan and convert a local folder
          recursively into CAR files ready to be onboarded to Filecoin Network.
          Singularity also indexes your files on IPFS for easy retrieval.
      - headline: 2. Distribute the CAR files
        subhead: ''
        text: >
          Easily host an HTTP server with the CAR files to be downloaded by the
          storage provider. You can also send the CAR files offline if the files
          are too large.
      - headline: 3. Pick your storage providers
        subhead: ''
        text: >
          Use a solution for finding storage providers or [reach out on
          Slack](https://app.slack.com/client/TEHTVS1L6/C02GQUMFQVA). Most
          storage providers today are interested in taking verified deals, so
          you need to familiarize yourself with [Filecoin
          Plus](https://github.com/filecoin-project/filecoin-plus-large-datasets).&#x20;
      - headline: 4. Make storage deals
        text: >
          Leverage Lotus and Boost to automatically make deals with the storage
          providers of your choice.&#x20;
    navigationLabel: How it works
    _template: textCards
meta:
  pageTitle: Singularity
  pageDescription: An end-to-end solution for data onboarding on Filecoin
---

