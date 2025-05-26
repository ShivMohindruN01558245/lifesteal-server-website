---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: BLOODCRAFT SMP
      color: text-red
      type: TitleBlock
    subtitle: Minecraft Lifesteal SMP Server
    text: >
      Join the ultimate Minecraft Lifesteal experience! Battle, survive, and conquer in our custom SMP world. 
      Every heart matters - gain hearts by defeating opponents, lose them when you fall. 
      
      🔥 **Server IP:** play.lifesteal.space
      
      💬 Join our Discord community for updates, events, and to connect with other players!
    actions:
      - label: "Copy Server IP"
        altText: "Copy play.lifesteal.space to clipboard"
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: "copy-ip-btn"
        type: Button
      - label: "Join Discord"
        altText: "Join our Discord server"
        url: https://discord.gg/bloodcraft
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ""
        type: Link
    media:
      url: /images/bloodcraft-logo.png
      altText: Bloodcraft SMP Server Logo
      elementId: ""
      type: ImageBlock
    badge:
      label: "play.lifesteal.space"
      color: text-red
      type: Badge
    elementId: ""
    colors: bg-dark-fg-red
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-20
          - pl-16
          - pb-20
          - pr-16

  - type: FeaturedItemsSection
    title:
      text: Key Features
      color: text-red
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: What makes Bloodcraft SMP special
    items:
      - type: FeaturedItem
        title: "❤️ Lifesteal Mode"
        subtitle: "Hearts Matter"
        text: >-
          Gain hearts by defeating other players and lose hearts when you die. 
          Strategic combat where every battle counts. Can you become the strongest?
        actions: []
        elementId: null
        colors: bg-dark-fg-red
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
            textAlign: left
        image:
          type: ImageBlock
          altText: Lifesteal hearts icon
          elementId: ""
          url: /images/lifesteal-icon.svg
          styles:
            self:
              borderRadius: x-large
      - title: "⚔️ Custom Events"
        subtitle: "Epic Battles"
        text: >-
          Regular events including tournaments, treasure hunts, and massive PvP battles. 
          Compete for exclusive rewards and bragging rights in our community.
        image:
          url: /images/events-icon.svg
          altText: Custom events icon
          elementId: ""
          type: ImageBlock
        actions: []
        colors: bg-dark-fg-red
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            textAlign: left
            justifyContent: center
        type: FeaturedItem
      - title: "🏰 Friendly Community"
        subtitle: "Active Players"
        text: >-
          Join hundreds of active players in our welcoming community. 
          Make allies, form teams, or go solo - the choice is yours in Bloodcraft SMP.
        image:
          url: /images/community-icon.svg
          altText: Community icon
          elementId: ""
          type: ImageBlock
        actions: []
        colors: bg-dark-fg-red
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
        type: FeaturedItem
    actions:
      - label: "Join Now"
        altText: "Join the server now"
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ""
        type: Button
    badge:
      label: "Server Features"
      color: text-red
      styles:
        self:
          textAlign: center
      type: Badge
    elementId: ""
    variant: three-col-grid
    colors: bg-dark-fg-red
    styles:
      self:
        padding:
          - pb-16
          - pt-16
          - pl-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center

  # Discord Section is moved up here!
  - title:
      text: "Community & Events"
      color: text-red
      type: TitleBlock
    subtitle: "Join our active Discord community"
    text: >
      Connect with fellow players, participate in tournaments, and stay updated 
      on server events. Our Discord is the hub for all Bloodcraft SMP activities.
    actions:
      - label: "Join Discord"
        url: https://discord.gg/bloodcraft
        icon: arrowRight
        iconPosition: right
        style: secondary
        type: Button
      - label: "Event Calendar"
        url: /events
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        type: Link
    media:
      url: /images/discord-community.svg
      altText: Discord community illustration
      type: ImageBlock
    badge:
      label: "Active Community"
      color: text-red
      type: Badge
    colors: bg-dark-fg-red
    styles:
      self:
        alignItems: center
        flexDirection: row-reverse
    type: GenericSection

  - subtitle: "Trusted by Minecraft players worldwide"
    images:
      - url: /images/minecraft-logo.svg
        altText: Minecraft logo
        type: ImageBlock
        styles:
          self:
            width: 60px
            height: 60px
      - url: /images/lifesteal-badge.svg
        altText: Lifesteal mode badge
        type: ImageBlock
        styles:
          self:
            width: 60px
            height: 60px
      - url: /images/smp-badge.svg
        altText: SMP server badge
        type: ImageBlock
        styles:
          self:
            width: 60px
            height: 60px
      - url: /images/pvp-badge.svg
        altText: PvP enabled badge
        type: ImageBlock
        styles:
          self:
            width: 60px
            height: 60px
      - url: /images/events-badge.svg
        altText: Custom events badge
        type: ImageBlock
        styles:
          self:
            width: 60px
            height: 60px
      - url: /images/community-badge.svg
        altText: Active community badge
        type: ImageBlock
        styles:
          self:
            width: 60px
            height: 60px
      - url: /images/24-7-badge.svg
        altText: 24/7 uptime badge
        type: ImageBlock
        styles:
          self:
            width: 60px
            height: 60px
    motion: move-to-left
    colors: bg-dark-fg-red
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
    type: ImageGallerySection

  - posts:
      - content/pages/blog/server-update-1.md
      - content/pages/blog/lifesteal-guide.md
      - content/pages/blog/community-spotlight.md
    showThumbnail: true
    showDate: true
    showAuthor: true
    variant: three-col-grid
    colors: bg-dark-fg-red
    styles:
      self:
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
    type: FeaturedPostsSection
    hoverEffect: move-up

  - title: "Divider"
    colors: bg-dark-fg-red
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection

  - title:
      text: "Ready to Start Your Adventure?"
      color: text-red
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: "Join thousands of players in the ultimate Lifesteal experience"
    text: |-
      Connect to play.lifesteal.space and begin your journey in Bloodcraft SMP. 
      Whether you're a seasoned PvP veteran or new to Lifesteal mode, our server 
      offers the perfect balance of challenge and fun. Build your base, gather resources, 
      and prepare for battle in our thriving Minecraft community.
    media:
      title: "Bloodcraft SMP Gameplay Trailer"
      url: /images/bloodcraft-trailer.mp4
      controls: true
      aspectRatio: '16:9'
      styles:
        self:
          padding:
            - pt-2
            - pb-2
            - pl-2
            - pr-2
          borderColor: border-red
          borderStyle: solid
          borderWidth: 2
          borderRadius: large
      type: VideoBlock
      autoplay: false
      loop: false
      muted: false
    badge:
      label: "Server Trailer"
      color: text-red
      styles:
        self:
          textAlign: center
      type: Badge
    colors: bg-dark-fg-red
    styles:
      self:
        flexDirection: col
        justifyContent: center
      subtitle:
        textAlign: center
    type: GenericSection

  - type: GenericSection
    title:
      text: "Server Rules & Guidelines"
      color: text-red
      styles:
        self:
          textAlign: left
      type: TitleBlock
    subtitle: "Play fair, have fun, respect others"
    text: |-
      Our server maintains a fun and fair environment for all players. 
      Basic rules include no hacking, no griefing spawn areas, and respect 
      for all community members. PvP is encouraged everywhere except spawn zones. 
      Check our Discord for the complete rulebook and updates.
    actions:
      - label: "Read Full Rules"
        url: /rules
        icon: arrowRight
        iconPosition: right
        style: secondary
        type: Button
      - label: "Report Issues"
        url: /support
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        type: Link
    media:
      title: "Server Rules Overview"
      url: /images/rules-preview.mp4
      autoplay: true
      loop: true
      muted: true
      controls: false
      aspectRatio: '16:9'
      styles:
        self:
          padding:
            - pt-2
            - pb-2
            - pl-2
            - pr-2
          borderColor: border-red
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: VideoBlock
    elementId: null
    colors: bg-dark-fg-red
    styles:
      self:
        flexDirection: row
        justifyContent: center
      subtitle:
        textAlign: left

  - title:
      text: "PvP Combat System"
      color: text-red
      type: TitleBlock
    subtitle: "Master the art of Lifesteal combat"
    text: >
      Our unique Lifesteal system adds strategy to every fight. Learn combat mechanics, 
      heart management, and advanced PvP techniques to dominate the battlefield.
    actions:
      - label: "Combat Guide"
        url: /pvp-guide
        icon: arrowRight
        iconPosition: right
        style: secondary
        type: Button
      - label: "Practice Arena"
        url: /arena
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        type: Link
    media:
      url: /images/pvp-combat.svg
      altText: PvP combat illustration
      type: ImageBlock
    badge:
      label: "Combat System"
      color: text-red
      type: Badge
    colors: bg-dark-fg-red
    styles:
      self:
        alignItems: center
    type: GenericSection

  - title: "Divider"
    colors: bg-dark-fg-red
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection

  - type: CarouselSection
    title: null
    subtitle: "What our players say about Bloodcraft SMP"
    items:
      - title: >-
          "Best Lifesteal server I've ever played on! The community is amazing and the PvP is intense."
        tagline: "Player Review"
        subtitle: "MinecraftPro2024, Discord"
        text: >-
          Been playing for months now and the server keeps getting better. 
          Regular events, active staff, and the Lifesteal mechanics are perfectly balanced.
        image:
          url: /images/player-avatar-1.png
          altText: Player avatar
          styles:
            self:
              borderRadius: full
          type: ImageBlock
        actions: []
        colors: bg-dark-fg-red
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
      - title: >-
          "Great server with fair rules and active moderation. Perfect place to learn Lifesteal PvP!"
        tagline: "Player Review"
        subtitle: "CraftMaster, In-Game"
        text: >-
          Started as a beginner and the community helped me improve. 
          Now I'm competing in tournaments and having a blast!
        image:
          url: /images/player-avatar-2.png
          altText: Player avatar
          styles:
            self:
              borderRadius: full
          type: ImageBlock
        actions: []
        colors: bg-dark-fg-red
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
      - title: >-
          "The custom events are incredible! Always something exciting happening on Bloodcraft."
        tagline: "Player Review"
        subtitle: "PvPKing99, Discord"
        text: >-
          Love the variety of events and challenges. The server never gets boring 
          and there's always a new goal to work towards.
        image:
          url: /images/player-avatar-3.png
          altText: Player avatar
          styles:
            self:
              borderRadius: full
          type: ImageBlock
        actions: []
        colors: bg-dark-fg-red
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
      - title: >-
          "Friendly staff, great community, and the best Lifesteal experience you can find!"
        tagline: "Player Review"
        subtitle: "RedstoneWiz, Discord"
        text: >-
          Been part of many servers but Bloodcraft feels like home. 
          The balance between PvP and community is perfect.
        image:
          url: /images/player-avatar-4.png
          altText: Player avatar
          styles:
            self:
              borderRadius: full
          type: ImageBlock
        actions: []
        colors: bg-dark-fg-red
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
      - title: >-
          "Amazing server with constant updates and improvements. Highly recommend!"
        tagline: "Player Review"
        subtitle: "BlockBuilder2023, In-Game"
        text: >-
          The developers really care about the player experience. 
          Regular updates and they actually listen to community feedback.
        image:
          url: /images/player-avatar-5.png
          altText: Player avatar
          styles:
            self:
              borderRadius: full
          type: ImageBlock
        actions: []
        colors: bg-dark-fg-red
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
      - title: >-
          "Join Bloodcraft SMP - you won't regret it! Best Minecraft server experience ever."
        tagline: "Player Review"
        subtitle: "DiamondHunter, Discord"
        text: >-
          From newbie-friendly guidance to hardcore PvP action, 
          this server has everything a Minecraft player could want.
        image:
          url: /images/player-avatar-6.png
          altText: Player avatar
          styles:
            self:
              borderRadius: full
          type: ImageBlock
        actions: []
        colors: bg-dark-fg-red
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
    elementId: null
    variant: next-prev-nav
    colors: bg-dark-fg-red
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center

  - title:
      text: "Server Features & Plugins"
      color: text-red
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: "Enhanced gameplay with custom features"
    items:
      - title: "Lifesteal Core"
        tagline: "Heart System"
        subtitle: "Gain and lose hearts through combat"
        text: |
          Our custom Lifesteal plugin creates intense PvP battles where every heart counts.
        image:
          url: /images/lifesteal-core.svg
          altText: Lifesteal core feature
          styles:
            self:
              borderRadius: x-large
          type: ImageBlock
        colors: bg-dark-fg-red
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
        type: FeaturedItem
      - title: "Custom Events"
        tagline: "Regular Activities"
        subtitle: "Tournaments, hunts, and special events"
        text: |
          Weekly tournaments, treasure hunts, and seasonal events keep the server exciting.
        image:
          url: /images/custom-events.svg
          altText: Custom events feature
          styles:
            self:
              borderRadius: x-large
          type: ImageBlock
        colors: bg-dark-fg-red
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
        type: FeaturedItem
      - title: "Economy System"
        tagline: "Trade & Commerce"
        subtitle: "Player-driven economy with shops"
        text: |
          Set up shops, trade with players, and build your wealth in our balanced economy.
        image:
          url: /images/economy-system.svg
          altText: Economy system feature
          styles:
            self:
              borderRadius: x-large
          type: ImageBlock
        colors: bg-dark-fg-red
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
        type: FeaturedItem
    variant: three-col-grid
    colors: bg-dark-fg-red
    styles:
      self:
        padding:
          - pt-16
          - pl-8
          - pb-16
          - pr-8
        justifyContent: center
      subtitle:
        textAlign: center
    type: FeaturedItemsSection

  - title:
      text: "Join Bloodcraft SMP Today"
      color: text-red
      type: TitleBlock
    subtitle: "Ready to start your Lifesteal adventure?"
    text: |-
      Connect to our server and become part of the Bloodcraft community. 
      Whether you're here for intense PvP battles, building epic bases, or making new friends, 
      our server has something for everyone. Join us today and see why thousands of players 
      choose Bloodcraft SMP as their Minecraft home.
    media:
      fields:
        - name: username
          label: "Minecraft Username"
          hideLabel: false
          placeholder: "Enter your Minecraft username"
          isRequired: true
          width: full
          type: TextFormControl
        - name: discord
          label: "Discord Username (Optional)"
          hideLabel: false
          placeholder: "YourName#1234"
          isRequired: false
          width: full
          type: TextFormControl
        - name: experience
          label: "PvP Experience Level"
          hideLabel: false
          placeholder: "Beginner, Intermediate, or Advanced"
          width: full
          type: TextFormControl
      elementId: join-server-form
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-6
            - pr-6
          borderColor: border-red
          borderStyle: solid
          borderWidth: 2
          borderRadius: large
      type: FormBlock
      submitButton:
        type: SubmitButtonFormControl
        label: "Get Server Info"
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: null
    badge:
      label: "Server IP: play.lifesteal.space"
      color: text-red
      type: Badge
    colors: bg-dark-fg-red
    type: GenericSection

seo:
  metaTitle: "Bloodcraft SMP - Minecraft Lifesteal Server | play.lifesteal.space"
  metaDescription: "Join Bloodcraft SMP, the ultimate Minecraft Lifesteal server! Battle players, gain hearts, and survive in our thriving PvP community. Connect now at play.lifesteal.space"
  socialImage: /images/bloodcraft-social.jpg
  type: Seo
type: PageLayout
---
