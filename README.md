# Classless/Semantic Framework Prototype

Under Development

## Goals

- Semantic, tag focused styling
- Low number of classes
- Accessible, take advantage of `aria-` attributes
- Small bundle size

- Decouple styles into seperate modules, ability to pick and choose included styles

- Support classless version
- Support a `prose` class for styling markdown only

## CSS Variables

This is to document and 'lock in' the property names for the project so they dont have to be renamed and replaced later on *fingers crossed*

All values are not final and subject to change

- **--property**: `default value`

### Built in values

#### Colors:

- **--primary: `#0582d2`**
- **--primary-d1: `#054269`**
- **--primary-l1: `#6fc5fc`**
- **--primary-a1: `rgba(5, 130, 210, 0.25)`**
- **--valid: `#17921e`**
- **--valid-a1: `rgba(23, 146, 30, 0.25)`**
- **--warning: `#ffd302`**
- **--warning-a1: `rgba(255, 211, 2, 0.25)`**
- **--invalid: `#d40d12`**
- **--invalid-a1: `rgba(212, 13, 18, 0.25)`**
- **--gray: `#000`**
- **--gray-l1: `#141414`**
- **--gray-l2: `#292929`**
- **--gray-l3: `#3d3d3d`**
- **--gray-l4: `#525252`**
- **--gray-l5: `#666666`**
- **--gray-l6: `#7a7a7a`**
- **--gray-l7: `#8f8f8f`**
- **--gray-l8: `#a3a3a3`**
- **--gray-l9: `#b8b8b8`**
- **--gray-l10: `#cccccc`**
- **--gray-l11: `#e0e0e0`**
- **--gray-l12: `whitesmoke`**
- **--gray-a1: `rgba(0, 0, 0, 0.75)`**
- **--gray-a2: `rgba(0, 0, 0, 0.5)`**
- **--gray-a3: `rgba(0, 0, 0, 0.25)`**
- **--gray-a4: `rgba(0, 0, 0, 0.1)`**

#### Font Sizes

- **--fluid-0**: `clamp(0.88rem, 0.2vw + 0.84rem, 1rem)`
- **--fluid-1**: `clamp(1rem, 0.2vw + 0.96rem, 1.13rem)`
- **--fluid-2**: `clamp(1.1rem, 0.41vw + 1.02rem, 1.35rem)`
- **--fluid-3**: `clamp(1.21rem, 0.67vw + 1.08rem, 1.62rem)`
- **--fluid-4**: `clamp(1.33rem, 1vw + 1.14rem, 1.94rem)`
- **--fluid-5**: `clamp(1.46rem, 1.42vw + 1.2rem, 2.33rem)`
- **--fluid-6**: `clamp(1.61rem, 1.94vw + 1.25rem, 2.8rem)`
- **--fluid-7**: `clamp(1.77rem, 2.59vw + 1.29rem, 3.36rem)`
- **--fluid-8**: `clamp(1.95rem, 3.4vw + 1.31rem, 4.03rem)`
- **--fluid-9**: `clamp(2.14rem, 4.4vw + 1.32rem, 4.84rem)`
