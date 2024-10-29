# Programmer Hall of Fame 🏆

A community-curated list of programming pioneers who shaped the software industry. This repository serves as the data source for [https://www.trevorlasn.com/hall-of-fame](https://www.trevorlasn.com/hall-of-fame), celebrating the visionaries who laid the foundation for modern computing.

## About

These pioneers didn't just write code - they dreamed up entirely new ways of thinking. From Ada's first algorithm to today's innovations, each pioneer pushed the boundaries of what's possible. Their ideas live on in every line of code we write.

## Data Structure

Each programmer entry follows this structure:

```typescript
interface Programmer {
  id: string;          // kebab-case unique identifier
  name: string;        // Full name and optional nickname
  description: string; // Brief bio focusing on technical contributions
  year: string;        // Birth-Death or "Birth-present"
  mainContribution: string; // Primary technical contribution
}
```

## How to Nominate

We welcome nominations for programming pioneers who have made significant technical contributions to the field. Follow these steps:

1. Fork this repository
2. Add your nomination to `programmers.json`
3. Submit a Pull Request with the following information:
   - Brief explanation of why this person should be included
   - Links to supporting information about their contributions
   - Ensure the entry follows the data structure format

### Nomination Guidelines

A good nomination should be for someone who:

- Made significant technical contributions to computer science or software development
- Created tools, languages, or methodologies that influenced the industry
- Contributed to fundamental computer science concepts or implementation
- Advanced the field through technical innovation

We focus on technical contributors rather than business figures. While successful companies are important, this list celebrates those who advanced the craft of programming itself.

### What Makes a Good Entry

- Focus on technical achievements rather than business success
- Provide specific, verifiable contributions
- Keep descriptions concise and focused on impact
- Avoid marketing language or hyperbole
- Include only factual, well-documented information

## Code of Conduct

We're committed to maintaining a welcoming, inclusive environment for all contributors. Please:

- Be respectful in discussions and comments
- Focus on technical merits when discussing nominations
- Support claims with credible sources
- Welcome diverse perspectives and experiences

## Usage

The data is available via:

```bash
https://raw.githubusercontent.com/indreklasn/programmer-hall-of-fame/main/programmers.json
```

Feel free to use this data in your own projects (with attribution).

## License

MIT - feel free to use this data in your own projects.

## Contributing

Beyond nominations, we welcome:
- Corrections to existing entries
- Improved descriptions
- Additional verification sources
- Translations of entries

Please submit any changes via Pull Request.

## Questions?

Open an issue if you have questions or suggestions about the project structure or nomination process.
