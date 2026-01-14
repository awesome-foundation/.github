# awesome-foundation

A battle-tested, production-ready AWS infrastructure foundation built on years of real-world experience managing complex, high-scale systems.

## Overview

**awesome-foundation** is a collection of production-proven AWS infrastructure patterns and best practices, curated by [@allixsenos](https://github.com/allixsenos) from years of running large-scale applications in production.

This repository represents the distilled knowledge of managing AWS infrastructure that has successfully handled **100,000+ requests per second** across many complex services in production environments.

## What's Inside

The stack leverages the following AWS services, orchestrated through CloudFormation:

- **AWS ECS Fargate** - Container orchestration without managing servers
- **AWS RDS Aurora** - Highly available, scalable relational database
- **AWS CloudFormation** - Infrastructure as Code for reproducible deployments

All components have been battle-tested in production scenarios, ensuring reliability, scalability, and operational excellence.

## Roadmap

The awesome-foundation ecosystem consists of several repositories that work together to provide a complete AWS infrastructure solution:

1. **[dns](https://github.com/awesome-foundation/dns)** - Managing DNS records in a config-as-code way ✅ *Published*
2. **[core-infrastructure](https://github.com/awesome-foundation/core-infrastructure)** - Templates for base networking and foundational infrastructure ✅ *Published*
3. **[web-service](https://github.com/awesome-foundation/web-service)** - Example of running an ECS Fargate task on this foundation 🚧 *Q1 2026*
4. **[rds-aurora](https://github.com/awesome-foundation/rds-aurora)** - Example of running an RDS Aurora cluster on this foundation 🚧 *Q1 2026*

## Who Is This For?

This foundation is designed for:

- **Teams entering the AWS space** looking for a proven starting point
- **Engineers** who want to skip common pitfalls and jump straight to production-ready patterns
- **Organizations** seeking an opinionated, well-architected infrastructure foundation
- **Anyone** who wants to build on a solid foundation with room to grow

## Philosophy

awesome-foundation provides an **opinionated launching pad** that:

- ✅ Sets you up with production-ready infrastructure from day one
- ✅ Gives you room to grow and customize as you explore AWS
- ✅ Avoids common mistakes through battle-tested patterns
- ✅ Reduces time-to-production for new projects
- ✅ Follows AWS best practices and Well-Architected Framework principles

Rather than starting from scratch or navigating countless AWS services alone, you get a solid foundation built on real-world production experience.

## Getting Started

_Coming soon: Infrastructure templates, deployment guides, and best practices documentation._

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

Built and maintained by [@allixsenos](https://github.com/allixsenos) based on years of production experience scaling AWS infrastructure to handle massive traffic and complex service architectures.