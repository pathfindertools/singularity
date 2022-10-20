---
draft: true
blocks:
  - style:
      alignment: 'flex-row-reverse items-center items-center-vertical '
      padding: pt-48 pb-20 pr-20 pl-20
      featureImage: wpx-499 hpx- ml-auto
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
      minHeight: min-h-0
      fullWidth: false
      padding: pt-10 pb-10 pr-20 pl-20
    background:
      fillStyles: bg-black
    markup: <p class="text-white">I am an embed</p>
    navigationLabel: Embed
    _template: embed
  - style:
      textAlignment: text-left
      minHeight: min-h-0
      padding: pt-14 pb-20 pr-20 pl-20
      contentWidth: w-full
      columns: '2'
      labelStyles: text-black undefined text-xl mb-0 font-bold
      headlineStyles: text-white undefined text-6xl mb-10 font-bold
      subheadStyles: text-black undefined text-3xl mb-0 font-bold
      textStyles: text-black undefined text-lg mb-0 font-bold
      contentOrder: labelHeadingsContent
    cardStyle:
      fillStyles: bg-primary opacity-100
      padding: pt-5 pb-5 pr-5 pl-5
      borderStyles: border-white border-0
      imageStyles: ' undefined undefined mb-0'
      labelStyles: 'text-white undefined text-sm mb-0 '
      headlineStyles: 'text-white undefined text-2xl mb-0 '
      subheadStyles: 'text-white undefined text-lg mb-0 '
      textStyles: 'text-white undefined undefined mb-0 '
      buttonType: secondary
    background:
      fillStyles: bg-accent1
    label: ''
    headline: Made with Microgen
    subhead: ''
    body: ''
    items:
      - image:
          src: >-
            https://res.cloudinary.com/protocolai/image/upload/v1652799687/microgen/sustainable-blockchain_dqbwkm.jpg
        headline: Sustainable Blockchain Summit
        text: >
          Two days of talks, workshops and discussions on how we can work
          together to develop and build greener blockchain solutions.
        link: 'https://sbs.tech/'
        buttonLabel: Visit Site
      - image:
          src: >-
            https://res.cloudinary.com/protocolai/image/upload/v1652799682/microgen/consensus-factory_g7ol2z.jpg
        headline: 'Consensus Factory '
        text: >
          Consensus is at the heart of decentralised systems, having taken
          centre stage with the introduction of Nakamoto’s Proof-of-Work (PoW)
          algorithm.
        link: 'https://consensus-factory.io/'
        buttonLabel: Visit Site
      - image:
          src: >-
            https://res.cloudinary.com/protocolai/image/upload/v1652799690/microgen/vector-commitment_i0nrao.jpg
        headline: Vector Commitment Day
        text: >
          Vector commitments are powerful primitives that find applications in
          many blockchains protocols. The goal of this workshop is to survey the
          state of the art in research.
        link: 'https://cryptonet.vercel.app/'
        buttonLabel: Visit Site
      - image:
          src: >-
            https://res.cloudinary.com/protocolai/image/upload/v1652799685/microgen/large-data_ulkv86.jpg
        headline: Filecoin Large Data
        subhead: ''
        text: "[Filecoin](https://filecoin.io/)\_is an open Web3 alternative to cloud storage, with better interoperability and larger capacity at a lower cost.\n"
        link: 'https://largedata.filecoin.io/'
        buttonLabel: Visit Site
      - image:
          src: >-
            https://res.cloudinary.com/protocolai/image/upload/v1649882496/microgen/hackathons_z7pwah_ulntqb.png
        headline: Hackathons
        subhead: ''
        text: >
          With Filecoin and IPFS, we empower developers and entrepreneurs to
          solve significant problems and ship innovative applications.
        link: 'https://hackathons.filecoin.io/'
        buttonLabel: Visit Site
      - image:
          src: >-
            https://res.cloudinary.com/protocolai/image/upload/v1649882497/microgen/asia-season_sn2gv8_bj7ovk.png
        headline: Asia Hackathon Season
        subhead: ''
        text: >
          Join us on a journey across the universe of Filecoin and IPFS across
          four distinct hackathon events.
        link: 'https://hackathons.filecoin.io/asia-hackathon-season.html'
        buttonLabel: Visit Site
    navigationLabel: Made with Microgen
    _template: photoCards
meta:
  pageTitle: Singularity
  pageDescription: Make modern web 3.0 ready websites with a real-time visual editor.
---

