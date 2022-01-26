# Container

<WvParagraphGroup>Just a container</WvParagraphGroup>

```jsx
import WvParagraphGroup from '@wevisdemo/ui/components/container.{vue,jsx,svelte}';

<WvParagraphGroup>Just a container</WvParagraphGroup>;
```

## Props

| Name    | Type    | Default |
| ------- | ------- | ------- |
| heading | string  |         |
| small   | boolean | false   |

## Slot / Children

Items apeended after heading

## Examples

**With heading and slot**

<WvParagraphGroup heading="เป้าหมาย">
  <p>
    dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
  </p>
</WvParagraphGroup>

```jsx
<WvParagraphGroup heading="เป้าหมาย">
  <p>
    dummy text of the printing and typesetting industry. Lorem Ipsum has been
    the industry's standard dummy text ever since the 1500s, when an unknown
    printer took a galley of type and scrambled it to make a type specimen book.
    It has survived not only five centuries, but also the leap into electronic
    typesetting, remaining essentially unchanged. It was popularised in the
    1960s with the release of Letraset sheets containing Lorem Ipsum passages,
    and more recently with desktop publishing software like Aldus PageMaker
    including versions of Lorem Ipsum.
  </p>
</WvParagraphGroup>
```

**Small size**

<WvParagraphGroup small heading="เขียนโปรแกรม">
  <p>
    dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley
  </p>
</WvParagraphGroup>

```jsx
<WvParagraphGroup small heading="เขียนโปรแกรม">
  <p>
    dummy text of the printing and typesetting industry. Lorem Ipsum has been
    the industry's standard dummy text ever since the 1500s, when an unknown
    printer took a galley
  </p>
</WvParagraphGroup>
```