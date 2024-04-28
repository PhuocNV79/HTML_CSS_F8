CSS Units:
  Các đơn vị thường dùng là : 
    Tuyệt đôi: px
    Tương đối: 
      %: Bằng % so với thẻ cha nó
      rem: phụ thuộc vào thẻ html
      em: Sẽ phụ thuộc thằng gần nhất có khai báo thuộc tính đó
      vh: viewport heigh Chiều cao trình duyệt
      vw: viewport width Chiều rộng trình duyệt

CSS Box-sizing:
  Khi sử dụng box-sizing: border-box : thì trình duyệt sẽ hiểu à kích thước element được khai báo
  sẽ bao gồm padding, border

CSS background-clip: content-box;
  Khi muốn tạo background chỉ cho phần nội dung thì dùng thuộc tính ni

CSS pseudo-class Lớp giả
  :root
  :hover
  :active
  :first-child
  :last-child

CSS pseudo-element Phân tử giả
  ::before
  ::after
  ::first-letter
  ::first-line
  ::selection

CSS position
  relative
  absolute : phụ thuộc vào thằng cha gần nhất có thuộc tính position, chứ ko phải position:relative
  fixed : Sử dụng khi cần vị trí của element phụ thuộc vào vị trí của cửa sổ trình duyệt

CSS flex box
  display: flex|inline-flex
  flex-direction: row|colum
  flex-wrap: nowrap|wrap|wrap-reverse
  flex-basis: <length>
  justify-content: flex-start|flex-end|center|space-between|  space-around
  justify-self: flex-start|flex-end|center
  align-content: flex-start|flex-end|center
  align-self: flex-start|flex-end|center
  flex-grow: <number>
  flex-shrink: <number>
  flex: <number>
  order: number
  flex-flow: short hand cua flex-wrap va flex-direction