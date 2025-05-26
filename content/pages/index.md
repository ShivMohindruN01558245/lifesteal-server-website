title: Home
slug: /
sections:
  # HERO SECTION
  - type: HeroSection
    background:
      style: linear-gradient(135deg, #1a0000 0%, #330000 50%, #1a0000 100%)
      imageOverlay:
        url: /images/hero-bg-grid.svg # Add a faint SVG grid pattern for style
        opacity: 0.12
    colors: bg-dark-fg-red
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-32
          - pl-8
          - pb-32
          - pr-8
    badge:
      label: "play.lifesteal.space"
      color: text-red
      type: Badge
    title:
      text: "BLOODCRAFT SMP"
      color: text-red
      type: TitleBlock
      styles:
        self:
          fontSize: 5xl
          fontWeight: bold
          textShadow: true
    subtitle: Minecraft Lifesteal SMP Server
    text: |
      Join the <strong>ultimate Minecraft Lifesteal experience</strong>! Battle, survive, and conquer in our custom SMP world.<br>
      Every heart matters — gain hearts by defeating opponents, lose them when you fall.<br>
      <br>
      <span style="font-size:1.25rem; color:#ff6666;"><b>🔥 Server IP:</b> play.lifesteal.space</span>
      <br>
      <br>
      💬 Join our Discord community for updates, events, and to connect with other players!
    actions:
      - label: "📋 Copy Server IP"
        altText: "Copy play.lifesteal.space to clipboard"
        url: /
        showIcon: true
        icon: copy
        iconPosition: left
        style: secondary
        elementId: "copy-ip-btn"
        type: Button
      - label: "💬 Join Discord →"
        altText: "Join our Discord server"
        url: https://discord.gg/bloodcraft
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        type: Link
    media:
      url: /images/bloodcraft-logo.png
      altText: Bloodcraft SMP Server Logo
      styles:
        self:
          width: 320px
          height: 320px
          borderRadius: 2xl
          boxShadow: xl
          animation: pulse
      type: ImageBlock

  # FEATURE GRID
  - type: FeaturedItemsSection
    badge:
      label: "Server Features"
      color: text-red
      type: Badge
    title:
      text: "Key Features"
      color: text-red
      type: TitleBlock
      styles:
        self:
          textAlign: center
          fontSize: 4xl
    subtitle: "What makes Bloodcraft SMP special"
    items:
      - title: "❤️ Lifesteal Mode"
        subtitle: "Hearts Matter"
        text: |
          Gain hearts by defeating other players and lose hearts when you die.<br>
          <strong>Strategic combat where every battle counts.</strong> Our system is custom-balanced, anti-cheat protected, and makes every encounter intense. Will you become the strongest?
        image:
          url: /images/lifesteal-icon.svg
          altText: Lifesteal hearts icon
          type: ImageBlock
      - title: "⚔️ Custom Events"
        subtitle: "Epic Battles"
        text: |
          Weekly <strong>tournaments</strong>, <strong>treasure hunts</strong>, and massive PvP battles.<br>
          Compete for exclusive in-game rewards and Discord roles.
        image:
          url: /images/events-icon.svg
          altText: Custom events icon
          type: ImageBlock
      - title: "🏰 Friendly Community"
        subtitle: "Active Players"
        text: |
          Join <strong>hundreds of active players</strong> in our welcoming community.<br>
          <strong>Form teams, make friends,</strong> or go solo — the choice is yours.
        image:
          url: /images/community-icon.svg
          altText: Community icon
          type: ImageBlock
    actions:
      - label: "Join Now →"
        altText: "Join the server now"
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        type: Button
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pt-20
          - pb-20
          - pl-8
          - pr-8

  # BADGE/BRAND STRIP
  - type: ImageGallerySection
    subtitle: "Trusted by Minecraft players worldwide"
    images:
      - url: /images/minecraft-logo.svg
        altText: Minecraft logo
        type: ImageBlock
      - url: /images/lifesteal-badge.svg
        altText: Lifesteal mode badge
        type: ImageBlock
      - url: /images/smp-badge.svg
        altText: SMP server badge
        type: ImageBlock
      - url: /images/pvp-badge.svg
        altText: PvP enabled badge
        type: ImageBlock
      - url: /images/events-badge.svg
        altText: Custom events badge
        type: ImageBlock
      - url: /images/community-badge.svg
        altText: Active community badge
        type: ImageBlock
      - url: /images/24-7-badge.svg
        altText: 24/7 uptime badge
        type: ImageBlock
    motion: move-to-left
    colors: bg-dark-fg-red

  # TESTIMONIALS / REVIEWS
  - type: CarouselSection
    subtitle: "What our players say about Bloodcraft SMP"
    items:
      - title: "\"Best Lifesteal server I've ever played on! The community is amazing and the PvP is intense.\""
        subtitle: "MinecraftPro2024, Discord"
        tagline: "Player Review"
        text: |
          Been playing for months now and the server keeps getting better.<br>
          Regular events, active staff, and the Lifesteal mechanics are perfectly balanced.
        image:
          url: /images/player-avatar-1.png
          altText: Player avatar
          type: ImageBlock
      - title: "\"Great server with fair rules and active moderation. Perfect place to learn Lifesteal PvP!\""
        subtitle: "CraftMaster, In-Game"
        tagline: "Player Review"
        text: |
          Started as a beginner and the community helped me improve.<br>
          Now I'm competing in tournaments and having a blast!
        image:
          url: /images/player-avatar-2.png
          altText: Player avatar
          type: ImageBlock
      - title: "\"The custom events are incredible! Always something exciting happening on Bloodcraft.\""
        subtitle: "PvPKing99, Discord"
        tagline: "Player Review"
        text: |
          Love the variety of events and challenges.<br>
          The server never gets boring and there's always a new goal.
        image:
          url: /images/player-avatar-3.png
          altText: Player avatar
          type: ImageBlock
      - title: "\"Friendly staff, great community, and the best Lifesteal experience you can find!\""
        subtitle: "RedstoneWiz, Discord"
        tagline: "Player Review"
        text: |
          Been part of many servers but Bloodcraft feels like home.<br>
          The balance between PvP and community is perfect.
        image:
          url: /images/player-avatar-4.png
          altText: Player avatar
          type: ImageBlock
    variant: next-prev-nav
    colors: bg-dark-fg-red
    styles:
      self:
        padding:
          - pt-12
          - pb-12

  # EXTRA FEATURE PLUGINS SECTION
  - type: FeaturedItemsSection
    badge:
      label: "Server Features & Plugins"
      color: text-red
      type: Badge
    title:
      text: "Enhanced gameplay with custom features"
      color: text-red
      type: TitleBlock
      styles:
        self:
          textAlign: center
    items:
      - title: "Lifesteal Core"
        subtitle: "Heart System"
        tagline: "Gain and lose hearts through combat"
        text: |
          Our custom Lifesteal plugin creates intense PvP battles where every heart counts.
        image:
          url: /images/lifesteal-core.svg
          altText: Lifesteal core feature
          type: ImageBlock
      - title: "Custom Events"
        subtitle: "Regular Activities"
        tagline: "Tournaments, hunts, and special events"
        text: |
          Weekly tournaments, treasure hunts, and seasonal events keep the server exciting.
        image:
          url: /images/custom-events.svg
          altText: Custom events feature
          type: ImageBlock
      - title: "Economy System"
        subtitle: "Trade & Commerce"
        tagline: "Player-driven economy with shops"
        text: |
          Set up shops, trade with players, and build your wealth in our balanced economy.
        image:
          url: /images/economy-system.svg
          altText: Economy system feature
          type: ImageBlock
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pb-16
          - pl-8
          - pr-8

  # CALL TO ACTION / FORM
  - type: GenericSection
    badge:
      label: "Server IP: play.lifesteal.space"
      color: text-red
      type: Badge
    title:
      text: "Join Bloodcraft SMP Today"
      color: text-red
      type: TitleBlock
    subtitle: "Ready to start your Lifesteal adventure?"
    text: |
      Connect to our server and become part of the Bloodcraft community.<br>
      Whether you're here for intense PvP battles, building epic bases, or making new friends, our server has something for everyone.<br>
      <br>
      <strong>💡 Tip:</strong> Make sure to check our Discord for event announcements, guides, and player support!
    media:
      fields:
        - name: username
          label: "Minecraft Username"
          placeholder: "Enter your Minecraft username"
          isRequired: true
          width: full
          type: TextFormControl
        - name: discord
          label: "Discord Username (Optional)"
          placeholder: "YourName#1234"
          isRequired: false
          width: full
          type: TextFormControl
        - name: experience
          label: "PvP Experience Level"
          placeholder: "Beginner, Intermediate, or Advanced"
          width: full
          type: TextFormControl
      elementId: join-server-form
      type: FormBlock
      submitButton:
        label: "Get Server Info →"
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        type: SubmitButtonFormControl
    colors: bg-dark-fg-red

# SEO CONFIG
seo:
  metaTitle: "Bloodcraft SMP - Minecraft Lifesteal Server | play.lifesteal.space"
  metaDescription: "Join Bloodcraft SMP, the ultimate Minecraft Lifesteal server! Battle players, gain hearts, and survive in our thriving PvP community. Connect now at play.lifesteal.space"
  socialImage: /images/bloodcraft-social.jpg
  type: Seo
type: PageLayout
