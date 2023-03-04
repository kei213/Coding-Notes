## remove spacing between Image component and container, add this to parent
```
.wrapper {
  letter-spacing: 0;
  word-spacing: 0;
  font-size: 0;
}
```

## Image
```
<Image 
	src="/31005324107_f4695fbfd2_e.jpg" 
	alt="Vercel Logo" 
	height={257}
	width={500}
	layout="intrinsic"
	srcSet="1x 2x"
	priority={true}
	className= {styles.image}
/>
```