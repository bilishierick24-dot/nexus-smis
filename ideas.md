# Kenyan SMIS — Design Directions

## Three possible approaches

| Theme Name | Very Brief Intro | Probability |
| --- | --- | --- |
| Schoolhouse Ledger | A civic-modern operations console that feels calm, accountable, and instantly legible to a busy Kenyan school leader. Warm paper surfaces meet deep institutional green and precise information hierarchy. | 0.07 |
| Learning Courtyard | A welcoming education platform inspired by an open school courtyard, using terracotta, natural light, and generous breathing room to bring human warmth to administrative tasks. | 0.04 |
| Signal Room | A high-clarity command centre with darker ink panels and lime signal states, emphasizing live attendance, approvals, and fast operational response. | 0.09 |

## Chosen approach — Schoolhouse Ledger

### Design Movement

**Civic Modernism with East African wayfinding.** The interface borrows the dependable visual language of public-service signage and a school record book, then resolves it into a contemporary digital operating system.

### Core Principles

1. **Read the school at a glance:** every surface earns its space through a decision, an action, or a meaningful status.
2. **Warm institutional clarity:** documents, registers, and official school records become approachable through paper-toned layers, strong type hierarchy, and measured color.
3. **Action stays close to context:** attendance, approvals, and financial follow-up are visible where decisions happen, not hidden in secondary menus.
4. **Mobile dignity:** controls stay generous, labels stay explicit, and the most time-sensitive tasks retain priority on narrow screens.

### Color Philosophy

The canvas is **Chalk Paper**—a warm, low-glare ivory that respects extended use in busy school offices. **Boma Green** grounds navigation, trust, and primary actions; its relationship to the familiar landscape should feel Kenyan without resorting to flags or clichés. Amber is reserved for needs-attention states, while ink and eucalyptus shades provide controlled information contrast. The single ownable signature color is **Boma Green (`#1D6A57`)**.

### Layout Paradigm

The application is a **left-hand working rail plus staggered ledger sheets**, not a centered card wall. A firm navigation rail carries school identity and role context; the main workspace uses offset information bands, a prominent morning briefing, and a right-side alert edge. On mobile, the rail becomes a compact top context bar and the day’s most urgent actions rise to the surface first.

### Signature Elements

1. **Ledger tabs:** small colored edge tabs identify sections and status categories.
2. **Register ticks:** hand-check-inspired circular status markers make attendance and completion states understandable at a glance.
3. **Pencil-line dividers:** fine muted rules and offset headers organize lists with the care of a well-kept class register.

### Interaction Philosophy

The product should feel reassuring rather than theatrical. High-frequency actions are immediate, clear, and reversible when appropriate. Hover states lift subtly, editable rows reveal a focused action affordance, and placeholder actions acknowledge intent with a plain-language notice.

### Animation

Motion is quiet and operational: panels enter with 160–220ms opacity and 6px vertical movement using a decisive ease-out; navigation changes use a 140ms color and background transition; buttons compress to 97% while pressed. Alerts pulse only once when new, rather than continually competing for attention. Non-essential animation is disabled when reduced motion is requested.

### Typography System

**DM Sans** provides efficient, highly legible UI text at small sizes. **Newsreader** supplies rare, editorial emphasis for the morning briefing and page-level statements, giving school leadership moments of considered reflection without compromising utilitarian clarity. Labels are compact, tracked DM Sans; main headings use weight and spacing before size; data values are tabular where possible.

### Brand Essence

**Kenyan SMIS is the daily operating desk for Kenyan schools that need every learner, shilling, and school day accounted for.** Its personality is **dependable, calm, and decisive**.

### Brand Voice

Headlines are direct and grounded in school activity. Calls to action name the real task rather than a generic outcome; microcopy is plain, respectful, and accountable.

> “See the school day clearly.”

> “Mark today’s register”

### Wordmark & Logo

The mark is an abstract **open register / rising path**: two parallel paper leaves form a compact shield-like doorway, while a centered checkline implies verified attendance and forward progress. It is used as a bold Boma Green graphic symbol without text; the wordmark is set in tailored DM Sans with a slightly widened rhythm, never a default logo lockup.

## Style Decisions

Ledger surfaces use **visible ruled paper, a Boma Green top edge, staggered sheet shadows, and warm ochre page tabs**. This system replaces generic card language throughout the workspace. Boma Green remains reserved for navigation, primary actions, institutional emphasis, and positive verified states. Kenyan imagery must centre dignified operational moments—staff registers, bursar work, school offices, gates, or classrooms—rather than broad interchangeable education scenes.
