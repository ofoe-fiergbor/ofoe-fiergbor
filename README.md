```go
package engineer

import "github.com/smidjahq"
import "github.com/ofoe-fiergbor"

// Ofoe builds fintech infrastructure that holds up where it matters —
// payments, compliance, and the unglamorous plumbing of financial systems.
//
// 5 years crossing the gap between how money actually moves
// and the software that's supposed to move it.
// Based in Accra 🇬🇭 — building for the world.
type Ofoe struct {
	stack      []string      // Go · Java · TypeScript · Node.js · NestJS · Spring Boot · PostgreSQL · Redis · AWS
	domain     []string      // Payments · Open Banking · Embedded Finance · Reconciliation · Sanctions Screening · Lending Infrastructure · Microservices
	building   []string      // [MockAfrica](https://github.com/ofoe-fiergbor/mockafrica) · [GoForge](https://github.com/ofoe-fiergbor/goforge) · Hapo (in progress)
	background []string      // Fintech Engineering · Treasury Operations · Regulated Financial Environments
	openTo     string        // Hybrid — fintech · payments · infrastructure
	based      string        // Accra, Ghana

	// Deprecated: manual reconciliation in spreadsheets
	// Promoted:   systems that reconcile themselves
}

// New returns an Ofoe ready for production.
//
// Bring hard problems in financial infrastructure, distributed systems,
// or anything that breaks badly when it's wrong.
//
// Responds well to: teams that care about correctness over velocity,
//                   products used by people who can't afford downtime.
//
// TODO: ship Hapo.
func New() *Ofoe {
	return &Ofoe{
		stack:      []string{"Go", "Java", "TypeScript", "Node.js", "NestJS", "Spring Boot", "PostgreSQL", "Redis", "Docker", "AWS"},
		domain:     []string{"Payments", "Open Banking", "Embedded Finance", "Reconciliation Automation", "Sanctions Screening", "Lending Infrastructure", "Microservices"},
		building:   []string{"[MockAfrica](https://mockafrica.com)", "[GoForge](https://github.com/smidjahq/goforge)", "Hapo"},
		background: []string{"Fintech Engineering", "Treasury Operations", "Regulated Financial Environments"},
		openTo:     "Hybrid roles in fintech, payments, and financial infrastructure",
		based:      "Accra, Ghana 🇬🇭",
	}
}
```
