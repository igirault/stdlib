set(
  fppFiles
  "test_ppoly.fypp"
)
fypp_f90("${fyppFlags}" "${fppFiles}" outFiles)

ADDTEST(ppoly)
