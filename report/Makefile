filename=`date "+%Y-%m-%d_%H-%M"`_$(PART).docx

docx:
	killall -9 "Microsoft Word" &
	pandoc src/$(PART).rst -s -o build/$(filename)
	open -a "Microsoft Word" build/$(filename)