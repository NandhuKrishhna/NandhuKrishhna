// Profile: Nandhu Krishna

class Developer {
  constructor() {
    this.name = "Nandhu Krishna";
    this.role = "Full Stack Developer";
    this.bio = "Too lazy to write a proper bio, so here's this instead.";
    this.status = [
      "Sometimes I build cool stuff.",
      "Sometimes I refactor it.",
      "Mostly, I just vibe here."
    ];
  }

  vibe() {
    console.log(`👋 Hey, I'm ${this.name}`);
    console.log(this.bio);
    this.status.forEach(line => console.log(line));
  }
}

const nandhu = new Developer();
nandhu.vibe();
